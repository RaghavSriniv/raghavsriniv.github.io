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
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
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
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Public Engagement'
      subtitle: 'Writing on macroeconomics for a broader audience'
      text: |-
        Alongside academic research, I write and speak on macroeconomic issues for general audiences — from Indian and Irish media to the [*Making Sense of Macroeconomics*](https://youtu.be/OkqtgYdBw-U?si=eF2BB0fKPA22lIDn) podcast.

        - [Making Sense of Macroeconomics](https://youtu.be/OkqtgYdBw-U?si=eF2BB0fKPA22lIDn) — podcast series, co-hosted with Chavi Mehta and Wajeeha Hamdani, on *YouTube*
        - [India's Economic Problems aren't About Currency or Gold: It's About AI](https://www.theindiaforum.in/forum/indias-economic-problems-arent-about-currency-or-gold-its-about-ai) — *The India Forum*, June 2026
        - [To stem rupee's slide, India should first fix its fragile domestic economy](https://scroll.in/article/1093348/to-stem-rupees-slide-india-should-first-fix-its-fragile-domestic-economy) — *Scroll.in*, June 2026
        - [India's export-led growth model](https://frontline.thehindu.com/economy/india-export-growth-structural-inequality-dual-economy/article69868430.ece) — *Frontline*, June 2025
        - [Explained: How US bond market fury stopped Trump's trade war](https://scroll.in/article/1081454/how-us-bond-market-fury-stopped-trumps-trade-war) — *Scroll.in*, April 2025
        - [On the fall in household savings](https://www.thehindu.com/business/Economy/on-the-fall-in-household-savings/article68092017.ece) — *The Hindu*, April 2024
        - [Investing in the care economy](https://www.thehindubusinessline.com/opinion/investing-in-the-care-economy/article34238269.ece) — *The Hindu Business Line*, April 2021
        - [Has economics lost its ability to relate to the real world?](https://www.rte.ie/brainstorm/2019/0516/1049834-has-economics-lost-its-ability-to-relate-to-the-real-world/) — *RTÉ Brainstorm*, May 2019
        - [Economists and austerity errors](https://www.irishtimes.com/opinion/letters/economists-and-austerity-errors-1.1397745) — *The Irish Times*, May 2013
        - The tyranny of the credit rating agencies — *LookLeft*, May 2013

        [See all public engagement →](/pub_engagement/)
    design:
      columns: '1'
  # - block: markdown
  #   content:
  #     title: 'My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: research
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collectiontest
  #   id: publications
  #   content:
  #     title: Books
  #     subtitle: aaa
  #     filters:
  #       folders:
  #         - books
  #       exclude_featured: false
  #   design:
  #     view: community/list_of_publications
  # - block: collection
  #   # id: publications
  #   content:
  #     title: Selected Journal Articles
  #     filters:
  #       folders:
  #         - articles
  #       exclude_featured: false
  #   design:
  #     view: community/list_of_publications
  # - block: collection
  #   # id: publications
  #   content:
  #     title: Selected Chapters in Books
  #     filters:
  #       folders:
  #         - chapters
  #       exclude_featured: false
  #   design:
  #     view: community/list_of_publications
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
