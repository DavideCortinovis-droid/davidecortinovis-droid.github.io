# davidecortinovis-droid.github.io

Personal academic website of Davide Cortinovis, Object Vision Group,
CIMeC, University of Trento — <https://davidecortinovis-droid.github.io>.

Built with [Jekyll](https://jekyllrb.com/) and deployed to GitHub Pages by
[`.github/workflows/publish.yaml`](.github/workflows/publish.yaml) on every push
to `main`. The Pages source is set to "GitHub Actions", not a branch.

## Editing the site

Everything on the page comes from the YAML files in `_data/`. There is a single
page (`index.html`) and a single layout (`_layouts/albertine.html`).

| File | What it drives |
| --- | --- |
| `_data/personal.yml` | Name, title, photo, contact details, profile links, the "Hello!" intro text |
| `_data/news.yml` | The News timeline. Newest first. `body` accepts markdown |
| `_data/publications.yml` | Journal articles and preprints |
| `_data/presentations.yml` | Conference talks, posters, and abstracts |
| `_data/projects.yml` | Projects. Currently empty, which hides the section |

Each list section is wrapped in `{% if site.data.<name>.size > 0 %}`, so
emptying a data file removes its section from the page.

The photo is `img/profile-picture.jpg`. The CV is not in this repo: `cv:` in
`_data/personal.yml` holds a Google Drive link, so it can be replaced without
a commit here. A repo-relative path such as `/uploads/resume.pdf` also works.

### The email address

`email_encoded` in `_data/personal.yml` is the address in base64. The page
decodes it in the browser only when a visitor clicks the envelope, so neither
this repo nor the served HTML holds a readable address for bulk harvesters to
scrape. It is not secrecy — anyone reading the page's JavaScript can decode it.

To change it:

```bash
python3 -c "import base64;print(base64.b64encode(b'new@address.here').decode())"
```

The `email` field beside it is the placeholder shown on hover before the click,
and the fallback for anyone browsing without JavaScript.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>. `bundle` pins the same `github-pages` gem the
CI build uses, so local output matches the deployed site.

## Credits

The design is the **Albertine** theme from
[elbowpatched-boilerplate](https://github.com/ianli/elbowpatched-boilerplate)
by [Ian Li](http://ianli.com), used under the MIT licence — see
[`LICENSE-albertine`](LICENSE-albertine). The layout has been adapted to add a
News section, to render conference citations and video links, and to update its
icon and CDN dependencies.
