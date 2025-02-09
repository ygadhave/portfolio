---
title: ''
date: 2022-10-24
type: landing

sections:
    
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
    
  - block: skills
    id: skills
    content:
      title: Skills
      text: ''
      username: admin
    design:
      columns: '1'


  - block: experience
    id: experience
    content:
      title: Experience

      title: Software Engineering Intern 
          company: Tech Diversified
          company_url: 'https://techdiversified.com'
          company_logo: asu
          location: Arizona
          date_start: '2024-08-21'
          date_end: ''
          description: |2-
              Responsibilities include:
    
              * Developed a scalable authentication system using Material UI and JWT, improving user session security.
              • Designed and optimized state management for dynamic UI views, enhancing performance on mobile & desktop.
              • Refactored React Native components to increase reusability by 25% and streamline API integrations and streamline API                    integrations.
              • Utilized MySQL, Elasticsearch and Docker to manage backend data efficiently.

    
      items:
        - title: Udergraduate Teaching Assistant - Digital Design(CSE120) 
          company: ARIZONA STATE UNIVERSITY
          company_url: 'https://www.asu.edu/'
          company_logo: asu
          location: Arizona
          date_start: '2023-01-10'
          date_end: '2024-12-10'
          description: |2-
              Responsibilities include:
    
              * Assisting students in circuit and microprocessor designs during the lectures and through ED discuscussions.
              * Collaborating with Professor Steven Millman to address design challenges.
              * Conducting weekly review sessions along with professor throughout the semester.
              * Organizing Final and Capstone specific review sessions towards the end of the semester to provide additional support and resolve queries related to the course material.
              * Fostering a supportive learning environment for mastering digital design concepts.

        - title: Udergraduate Teaching Assistant - Software Engineering(CSE360)
          company: ARIZONA STATE UNIVERSITY
          company_url: 'https://www.asu.edu/'
          company_logo: asu
          location: Arizona
          date_start: '2024-01-08'
          date_end: '2024-12-10'
          description: |2-
              Responsibilities include:
    
              * Conducting office hours to assist students with coding challenges in group projects.
              * Collaborating with the professor to develop tutorials, pop quizzes, and assignment rubrics.
              * Providing one-on-one guidance to students navigating software engineering concepts.
              * Fostering a positive and collaborative learning environment.
              * Contributing to the overall structure and quality of the course content.
              * Offering support beyond scheduled class times to ensure comprehensive assistance.
              * Actively participating in the development of effective teaching materials.
              * Dedicated to helping students succeed in understanding software engineering principles.
    
        - title: Udergraduate Teaching Assistant - Cyber Security(CSE365)
          company: ARIZONA STATE UNIVERSITY
          company_url: 'https://www.asu.edu/'
          company_logo: asu
          location: Arizona
          date_start: '2024-01-08'
          date_end: '2024-12-10'
          description: |2-
              Responsibilities include:
    
              * Leading in-person recitations to address doubts on Python scripts and cybersecurity challenges.
              * Providing continuous support to students via Discord throughout the day.
              * Ensuring accessibility and assistance beyond scheduled class times.
              * Facilitating a dynamic and engaging learning atmosphere to encourage active participation.
              * Contributing to the development of effective teaching materials for cybersecurity principles.
    design:
      columns: '2'

  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://coursera.org/share/5c08a4fc1ca8bbfd4ff2afa4fb31a66b
          date_end: ''
          date_start: '2023-08-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Introduction to Structured Query Language (SQL)
          url: ''
        - certificate_url: https://coursera.org/share/3f290f8dc110aae7c60ea7d8e5bbd04e
          date_end: ''
          date_start: '2024-01-24'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Crash Course on Python
          url: ''

    design:
      columns: '2'

#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
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
#      view: compact
#      columns: '2'


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
        - name: Deep Learning
          tag: Deep Learning
        - name: Game Development
          tag: Game Development
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false


  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'


  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card


  # - block: collection
  #   content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation


  # - block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  # - block: tag_cloud
  #   content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
  #    # text: |-
  #    # Use the following information to connect with me, if you have any questions about my projects or want to network.
  #    # Contact (add or remove contact options as necessary)
      email: yashwantng2003@gmail.com
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/ygadhave018'
  #    # Automatically link email and phone or display as text?
  #    autolink: true
  #    # Email form provider
  #    form:
  #  provider: netlify
  #  formspree:
  #    id:
  #  netlify:
  #    # Enable CAPTCHA challenge to reduce spam?
  #    captcha: true
  #
    design:
      columns: '2'
---
