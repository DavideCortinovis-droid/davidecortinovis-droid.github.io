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
        <p style="color: green;">:speaking_head: 7 August 2025 :loudspeaker:</p>
        <p> New <span style="text-decoration: underline;"><a href="https://www.biorxiv.org/content/10.1101/2025.08.05.668643v1">preprint</a></span> on investigating action topography in visual cortex and deep artificial neural networks!!</p>      
        <br>
        <p style="color: green;">:speaking_head: 12 August 2025 at <span style="text-decoration: underline;"><a href="https://2025.ccneuro.org/">CNN</a></span> in Amsterdam, the Netherlands :loudspeaker:</p>
        <p>I will present a <span style="text-decoration: underline;"><a href="https://2025.ccneuro.org/abstract_pdf/Cortinovis_2025_Comparing_Object_Selectivity_Visual_Cortex_Topographic.pdf">poster</a></span> on comparing object selectivity in visual cortex and topographic deep neural networks.</p>      
        <br>
        <p style="color: green;">:speaking_head: 17 May 2025 at <span style="text-decoration: underline;"><a href="https://www.visionsciences.org/">VSS</a></span> in St Pete Beach, Florida, US :loudspeaker:</p>
        <p>I gave a <span style="text-decoration: underline;"><a href="https://www.visionsciences.org/presentation/?id=1910">talk</a></span> on object dimensions underlying food selectivity in visual cortex.</p>      
        <br>
        <p style="color: green;">:speaking_head: 22-27th June 2024 at OHBM in Seoul, South Korea :loudspeaker:</p>
        <p>I gave a talk on action-related topographic organization of category-selectivity in visual cortex and in artificial neural networks.</p>
      
      filters:
        folders:
          - news # todo not exist
    design:
      columns: '1'
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
        <p>1. <strong>Cortinovis, D.</strong>, Truong, N., Op de Beeck, H., &amp; Bracci, S. (2025). Investigating action topography in visual cortex and deep artificial neural networks. <em>Preprint.</em> [<span style="text-decoration: underline;"><a href="https://www.biorxiv.org/content/10.1101/2025.08.05.668643v1">Paper</a></span>]</p>
        <p>2. <strong>Cortinovis, D.</strong>, Peelen, M.V., &amp; Bracci, S. (2025). Tool Representations in Human Visual Cortex. <em>Journal of Cognitive Neuroscience.</em> [<span style="text-decoration: underline;"><a href="https://direct.mit.edu/jocn/article/37/3/515/125486">Paper</a></span>]</p>
              
      filters:
        folders:
          - publications # todo not yet
        exclude_featured: false
  - block: collection
    id: papers
    content:
      title: Conference abstracts
      text: |-
        <p>1. <strong>Cortinovis, D.</strong>, Hebart, M., & Bracci, S. (2025). Comparing Object Selectivity in Visual Cortex and Topographic Deep Artifcial Neural Networks. <em>Conference on Cognitive Computational Neuroscience.</em> [<span style="text-decoration: underline;"><a href="https://2025.ccneuro.org/abstract_pdf/Cortinovis_2025_Comparing_Object_Selectivity_Visual_Cortex_Topographic.pdf">Abstract</a></span>]</p>
        <p>2. <strong>Cortinovis, D.</strong>, Orlandi, G., van Campenhout, L., & Bracci, S. (2025). Object dimensions underlying food selectivity in visual cortex. <em>Journal of Vision, 25(9), 1910-1910.</em> [<span style="text-decoration: underline;"><a href="https://jov.arvojournals.org/article.aspx?articleid=2810196">Abstract</a></span>]</p>
        <p>3. Bracci, S., <strong>Cortinovis, D.</strong>, &amp; Garnuto, E. (2025). The Effect of Scene Clutter on Visual Representations. <em>Journal of Vision, 25(9), 2061-2061.</em> [<span style="text-decoration: underline;"><a href="https://jov.arvojournals.org/article.aspx?articleid=2810061">Abstract</a></span>]</p>
        <p>4. <strong>Cortinovis, D.</strong>, de Beeck, H. O., &amp; Bracci, S. (2023). The role of action-related properties in shaping the object space in the biological and artificial brain. <em>Journal of Vision, 23(9), 4868-4868.</em> [<span style="text-decoration: underline;"><a href="https://jov.arvojournals.org/article.aspx?articleid=2791637">Abstract</a></span>]</p>
        <p>5. <strong>Cortinovis, D.</strong>, de Beeck, H. O., &amp; Bracci, S. (2021). The organization of body-parts representations in Deep Convolutional Neural Networks. <em>Perception, 50(1_SUPPL), 123-123.</em></p>
      
      filters:
        folders:
          - publications # todo not yet
        exclude_featured: false
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
