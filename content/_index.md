---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: MRes Experimental Psychology with Data Science
          company: The University of Manchester
          company_url: 'https://www.manchester.ac.uk/'
          company_logo: 'UoM'
          location: Manchester, UK
          date_start: '2022-09-15'
          date_end: ''
        - title: Research Assistance
          company: Research Group Lead by Dr.Zeyang Yang
          company_url: ''
          company_logo: 'Soochow_University'
          location: Soochow, China
          date_start: '2021-09-01'
          date_end: '2022-06-30'
          description: |2-
              Responsibilities include:

              * Data Collecting
              * Programming
              * Data Analysing and Modeling
        - title: Bsc in Applied Psychology
          company: Soochow University
          company_url: 'https://www.suda.edu.cn/'
          company_logo: 'Soochow_University'
          location: Soochow, China
          date_start: '2020-09-01'
          date_end: '2022-06-30'
        - title: Evaluation & Academic Research Officers
          company: Youth Commonweal Practice Centre of Ningxia·Evaluation and Academic Research Department
          company_url: 'https://www.cyouthchange.org/'
          company_logo: Cyouthchange
          location: Yinchuan, China
          date_start: '2018-01-01'
          date_end: ''
          description: Monitor and evaluate the outcome & impact of the projects delivered by the Organization. Conduct academic research among the youth group in northwest China.
        - title: BEng in Metallurgical Engineering
          company: Soochow University
          company_url: 'https://www.suda.edu.cn/'
          company_logo: 'Soochow_University'
          location: Soochow, China
          date_start: '2016-09-01'
          date_end: '2020-06-30'
          description: |2-
              Gained mathematical training during this Undergraduate period, including:
              * Linear Algebra
              * Advanced Mathematics
              * Probability & Statistics
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_start: '2022-06-30'
          organization: Soochow University
          title: Outstanding Graduates
        - certificate_url: 
          date_end: ''
          date_start: '2021-06-30'
          description: ''
          organization: Soochow University
          organization_url: 
          title: Learning Excellent Scholarship - First Prize
          url: ''
        - date_start: '2021-06-30'
          organization: Soochow University
          title: Social Work Scholarship
        - date_start: '2021-06-30'
          organization: Soochow University
          title: Comprehensive Scholarship
        - date_start: '2020-06-30'
          organization: Soochow University
          title: National Third Prize
          description: The 3rd National College Student Metallurgical Science and Technology Competition
        - date_start: '2018-05-30'
          organization: National Computer Rank Examination
          title: Advanced Applications of MS Office
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Cyber Psychology
          tag: Cyber Psychology
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        🌟🌟🌟Please use the contact form below or email me directly if you have any questions or want to chat. I'll be there in no time.😊
      # Contact (add or remove contact options as necessary)
      email: xuwenting98@gmail.com
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: DM Me
          link: /#contact
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
