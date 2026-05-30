---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: centSer
          parallax: false
  - block: collection
    id: news
    content:
      title: 'News'
      subtitle: ''
      text: |-
        <div style="background: linear-gradient(145deg, #012b25, #03564f); padding: 1.25rem; border-radius: 14px; color: #d7f3e3; box-shadow: 0 10px 25px rgba(0,0,0,0.25);">
          <ol style="list-style: none; padding: 0; margin: 0; display: flex; flex-direction: column; gap: 0.9rem;">
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">8 May 2026</span>
              <span style="flex: 1;">My work on food selectivity in visual cortex received the <a style="color: #9ee8c7; text-decoration: underline;" href="https://drive.google.com/file/d/1-SocL9xnwCB2fm83OvzF40Tt1HdpW-Cs/view?usp=sharing">Best Poster Award</a> at <a style="color: #9ee8c7; text-decoration: underline;" href="https://event.unitn.it/cimec-caos/">CAOs Workshop</a>!</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">20 Apr 2026</span>
              <span style="flex: 1;"><b>I defended <a style="color: #9ee8c7; text-decoration: underline;" href="https://iris.unitn.it/bitstream/11572/483110/1/PhD_Thesis_Cortinovis.pdf">my thesis</a> and earned my PhD!</b></span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">13 Apr 2026</span>
              <span style="flex: 1;">A <a style="color: #9ee8c7; text-decoration: underline;" href="https://www.biorxiv.org/content/10.64898/2026.04.09.717525v1.abstract">preprint</a> based on one study from my PhD thesis is now available.</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">21 Dec 2025</span>
              <span style="flex: 1;">I published the main <a style="color: #9ee8c7; text-decoration: underline;" href="https://www.nature.com/articles/s41467-025-67855-6">paper</a> of my PhD thesis on <em>Nature Communications</em>: Investigating action topography in visual cortex and deep artificial neural networks!!</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">12 Aug 2025</span>
              <span style="flex: 1;"><b><a style="color: #9ee8c7; text-decoration: underline;" href="https://2025.ccneuro.org/">CCN</a> in Amsterdam, the Netherlands:</b> I presented a <a style="color: #9ee8c7; text-decoration: underline;" href="https://2025.ccneuro.org/abstract_pdf/Cortinovis_2025_Comparing_Object_Selectivity_Visual_Cortex_Topographic.pdf">poster</a> on comparing object selectivity in visual cortex and topographic deep neural networks.</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">17 May 2025</span>
              <span style="flex: 1;"><b><a style="color: #9ee8c7; text-decoration: underline;" href="https://www.visionsciences.org/">VSS</a> in St Pete Beach, Florida, US:</b> I gave a <a style="color: #9ee8c7; text-decoration: underline;" href="https://jov.arvojournals.org/article.aspx?articleid=2810196">talk</a> on object dimensions underlying food selectivity in visual cortex.</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">22–27 Jun 2024</span>
              <span style="flex: 1;"><b>OHBM in Seoul, South Korea:</b> I gave a <a style="color: #9ee8c7; text-decoration: underline;" href="https://www.youtube.com/watch?v=ws3nZaWWNvY">talk</a> on action-related topographic organization of category-selectivity in visual cortex and in artificial neural networks.</span>
            </li>
          </ol>
        </div>
      
      filters:
        folders:
          - news # todo not exist
    design:
      columns: '1'
      spacing:
        padding: [1.5rem, 0, 1.5rem, 0]
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 2
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
  - block: collection
    id: papers
    content:
      title: Publications
      text: |-
        <div style="background: linear-gradient(145deg, #012b25, #03564f); padding: 1.25rem; border-radius: 14px; color: #d7f3e3; box-shadow: 0 10px 25px rgba(0,0,0,0.25);">
          <ol style="list-style: none; padding: 0; margin: 0; display: flex; flex-direction: column; gap: 0.9rem;">
          <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">1</span>
              <span style="flex: 1;"><b>Cortinovis, D.</b>, Hebart, M., &amp; Bracci, S. (2026). Encoding models uncover fine-grained feature selectivity for bodies, hands and tools. <em>Biorxiv.</em> [<a style="color: #9ee8c7; text-decoration: underline;" href="https://www.biorxiv.org/content/10.64898/2026.04.09.717525v1.abstract">Preprint</a>]</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">2</span>
              <span style="flex: 1;"><b>Cortinovis, D.</b>, Truong, N., Op de Beeck, H., &amp; Bracci, S. (2025). Investigating action topography in visual cortex and deep artificial neural networks. <em>Nature Communications.</em> [<a style="color: #9ee8c7; text-decoration: underline;" href="https://www.nature.com/articles/s41467-025-67855-6">Paper</a>]</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">3</span>
              <span style="flex: 1;"><b>Cortinovis, D.</b>, Peelen, M.V., &amp; Bracci, S. (2025). Tool Representations in Human Visual Cortex. <em>Journal of Cognitive Neuroscience.</em> [<a style="color: #9ee8c7; text-decoration: underline;" href="https://direct.mit.edu/jocn/article/37/3/515/125486">Paper</a>]</span>
            </li>
          </ol>
        </div>
              
      filters:
        folders:
          - publications # todo not yet
        exclude_featured: false
    design:
      spacing:
        padding: [1.25rem, 0, 1.25rem, 0]
  - block: collection
    id: papers
    content:
      title: Conference abstracts
      text: |-
        <div style="background: linear-gradient(145deg, #012b25, #03564f); padding: 1.25rem; border-radius: 14px; color: #d7f3e3; box-shadow: 0 10px 25px rgba(0,0,0,0.25);">
          <ol style="list-style: none; padding: 0; margin: 0; display: flex; flex-direction: column; gap: 0.9rem;">
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">1</span>
              <span style="flex: 1;"><b>Cortinovis, D.</b>, Hebart, M., &amp; Bracci, S. (2025). Comparing Object Selectivity in Visual Cortex and Topographic Deep Artifcial Neural Networks. <em>Conference on Cognitive Computational Neuroscience.</em> [<a style="color: #9ee8c7; text-decoration: underline;" href="https://2025.ccneuro.org/abstract_pdf/Cortinovis_2025_Comparing_Object_Selectivity_Visual_Cortex_Topographic.pdf">Abstract</a>]</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">2</span>
              <span style="flex: 1;"><b>Cortinovis, D.</b>, Orlandi, G., van Campenhout, L., &amp; Bracci, S. (2025). Object dimensions underlying food selectivity in visual cortex. <em>Journal of Vision, 25(9), 1910-1910.</em> [<a style="color: #9ee8c7; text-decoration: underline;" href="https://jov.arvojournals.org/article.aspx?articleid=2810196">Abstract</a>]</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">3</span>
              <span style="flex: 1;">Bracci, S., <b>Cortinovis, D.</b>, &amp; Garnuto, E. (2025). The Effect of Scene Clutter on Visual Representations. <em>Journal of Vision, 25(9), 2061-2061.</em> [<a style="color: #9ee8c7; text-decoration: underline;" href="https://jov.arvojournals.org/article.aspx?articleid=2810061">Abstract</a>]</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">4</span>
              <span style="flex: 1;"><b>Cortinovis, D.</b>, de Beeck, H. O., &amp; Bracci, S. (2023). The role of action-related properties in shaping the object space in the biological and artificial brain. <em>Journal of Vision, 23(9), 4868-4868.</em> [<a style="color: #9ee8c7; text-decoration: underline;" href="https://jov.arvojournals.org/article.aspx?articleid=2791637">Abstract</a>]</span>
            </li>
            <li style="display: flex; align-items: center; gap: 0.75rem; line-height: 1.35;">
              <span style="background: #0a3a33; color: #d7f3e3; padding: 0.35rem 0.8rem; border-radius: 999px; font-weight: 700; white-space: nowrap;">5</span>
              <span style="flex: 1;"><b>Cortinovis, D.</b>, de Beeck, H. O., &amp; Bracci, S. (2021). The organization of body-parts representations in Deep Convolutional Neural Networks. <em>Perception, 50(1_SUPPL), 123-123.</em></span>
            </li>
          </ol>
        </div>
      
      filters:
        folders:
          - publications # todo not yet
        exclude_featured: false
    design:
      spacing:
        padding: [1.0rem, 0, 1.0rem, 0]
    # design:
    #   view: citation
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
            <p>Thanks <a href="https://tlmnhut.github.io/">Nhut Truong</a> for the help to make the page :innocent:</p>	
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
