---
# Leave the homepage title empty to use the site title
title: 'ASBhatia'
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Wowchemy demo site
    content:
      title: ASBhatia
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://wowchemy.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Wowchemy - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    #content:
    #  title: Skills
    #  items:
    #    - name: R
    #      description: 90%
    #      icon: r-project
    #      icon_pack: fab
    #    - name: Statistics
    #      description: 100%
    #      icon: chart-line
    #      icon_pack: fas
    #    - name: Photography
    #      description: 10%
    #      icon: camera-retro
    #      icon_pack: fas
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
        - title: Postdoctoral Research Associate
          company: Purdue University
          company_url: https://www.purdue.edu/
          #company_logo: org-gc
          location: Indiana, USA
          date_start: '2022-01-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Developing quantum/classical algorithms for different applications in STEM disciplines
              * Mentoring graduate students
        - title: Postdoctoral Researcher
          company: University of Tuebingen
          company_url: https://uni-tuebingen.de/en/
          #company_logo: org-x
          location: Tuebingen, Germany
          date_start: '2021-03-01'
          date_end: '2021-11-30'
          description: Developed quantum resilient algorithms for a portfolio optimization problem

        - title: Assistant Professor-Research
          company: Chitkara University
          company_url: https://www.chitkara.edu.in/
          #company_logo: org-x
          location: Patiala, India
          date_start: '2019-01-01'
          date_end: '2021-01-31'
          description: |2-
              Responsibilities include:

              * Mentoring students
              * Taught Undergraduate & Master's students 

        - title: Teaching Assistant
          company: Thapar University
          company_url: https://www.thapar.edu/
          #company_logo: org-x
          location: Patiala, India
          date_start: '2016-07-01'
          date_end: '2017-06-30'
          description: |2-
              Responsibilities include:

              * Assessments
              * Conducted and invigilated exams
              * Taught laboratory sections

        - title: Assistant Professor
          company: Maharaja Agrasen University
          company_url: https://mau.ac.in/
          #company_logo: org-x
          location: Baddi, India
          date_start: '2014-07-01'
          date_end: '2015-07-31'
          description: |2-
              Responsibilities include:

              * Taught Undergraduate & Master's students 
            
        - title: Assistant Professor
          company: IEC University 
          company_url: https://www.iecuniversity.ac.in/
          #company_logo: org-x
          location: Baddi, India
          date_start: '2013-07-01'
          date_end: '2014-06-30'
          description: |2-
              Responsibilities include:

              * Cordinator First year Undergraduate
              * Taught Undergraduate students 

        - title: Software Trainee
          company: Center for Development of Advanced Computing (CDAC)
          company_url: https://www.cdac.in/index.aspx?id=ML
          #company_logo: org-x
          location: Mohali, India
          date_start: '2010-01-01'
          date_end: '2010-06-30'
          description: |2-
              Responsibilities include:

              * Gained practical experience 
              * Worked on projects and reports
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      count: 3
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.credly.com/badges/ed1a47d1-7f45-4182-bbdb-de7a16596d2a
          date_end: ''
          date_start: '2021-08-01'
          description: ''
          organization: IBM
          #organization_url: https://qiskit.org/
          title: IBM Qiskit Advocate
          url: https://qiskit.org/advocates

        - certificate_url: https://www.credly.com/badges/de3be225-455f-40b8-9139-f41b7f64da4d
          date_end: ''
          date_start: '2021-07-14'
          description: ''
          organization: IBM
          #organization_url: https://www.edx.org
          title: IBM Associate Certified Developer-Quantum
          url: https://www.credly.com/badges/de3be225-455f-40b8-9139-f41b7f64da4d

        - certificate_url: https://www.credly.com/badges/dcd1bc00-a112-4840-99b4-60c6ef7277ef
          #date_end: '2021-12-21'
          date_start: '2022-11-28'
          description: ''
          organization: IBM
          #organization_url: https://www.datacamp.com
          title: 'IBM Quantum Challenge Fall 2022 Achievement - Advanced'
          url: 'https://www.credly.com/badges/dcd1bc00-a112-4840-99b4-60c6ef7277ef'

        - certificate_url: https://www.credly.com/badges/7b26893c-400c-4291-8a0d-c67ecc424d24
          #date_end: '2021-12-21'
          date_start: '2021-06-12'
          description: ''
          organization: IBM
          #organization_url: https://www.datacamp.com
          title: 'IBM Quantum Challenge 2021 Achievement - Advanced'
          url: 'https://www.credly.com/badges/7b26893c-400c-4291-8a0d-c67ecc424d24'

        - certificate_url: https://www.credly.com/badges/24d4c5b2-c415-4a61-aeb7-25f76b3fbf1c
          #date_end: '2021-12-21'
          date_start: '2021-02-04'
          description: ''
          organization: IBM
          #organization_url: https://www.datacamp.com
          title: 'IBM Quantum Practitioner - Certificate'
          url: 'https://www.credly.com/badges/24d4c5b2-c415-4a61-aeb7-25f76b3fbf1c'

        - certificate_url: https://www.credly.com/badges/61f9fa0e-701a-4205-8571-2dc8891fdf96
          #date_end: '2021-12-21'
          date_start: '2020-12-11'
          description: ''
          organization: IBM
          #organization_url: https://www.datacamp.com
          title: 'IBM Quantum Challenge - Fall 2020 - Advanced'
          url: 'https://www.credly.com/badges/61f9fa0e-701a-4205-8571-2dc8891fdf96'

    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
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
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
      # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
      count: 3
    design:
      columns: '2'
      view: Compact
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- #block: tag_cloud
    #content:
    #  title: Popular Topics
    #design:
    #  columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: bhatia87@purdue.edu, drasinghbhatia@gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 516 Northwestern Ave
        city: West Lafayette
        region: IN
        postcode: '47906'
        country: United States
        country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
        #- 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      #contact_links:
        #- icon: twitter
          #icon_pack: fab
          #name: DM Me
          #link: 'https://twitter.com/Twitter'
        #- icon: skype
          #icon_pack: fab
          #name: Skype Me
          #link: 'skype:echo123?call'
        #- icon: video
          #icon_pack: fas
          #name: Zoom Me
          #link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
