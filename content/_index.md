---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: The Forrest Lab
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  
  - block: portfolio
    id: overview
    content:
      sort_ascending: true
      buttons:
        - name: All
          tag: '*'
        - name: Eating disorders
          tag: Eating disorders
        - name: Suicide
          tag: Suicide
        - name: Quant
          tag: Quant
      default_button_index: 0
      title: Research Overview
      filters:
        folders:
          - project_overview
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
     
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows? note to self: used to be in showcase view
      flip_alt_rows: true

  - block: portfolio
    id: current
    content:
      title: Current Projects
      sort_ascending: true
      filters:
        folders:
          - project_current
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true

  - block: portfolio
    id: team
    content:
      sort_ascending: true
      buttons:
        - name: All
          tag: '*'
        - name: PhD students
          tag: PhD students
        - name: Staff
          tag: Staff
      default_button_index: 0
      title: Research Team
      filters:
        folders:
          - team
    design:
      columns: '1'
      view: masonry


  - block: portfolio
    id: applicants
    content:
      title: 2025 Applicants
      subtitle: <br><br>**I am accepting a clinical psychology PhD student** to begin at the [University of Oregon](https://naturalsciences.uoregon.edu/psychology) in **Fall 2025** (meaning I'll review applications that are submitted 12/2024).
      text: This section contains important info for prospective students potentially interested in joning the lab. Start at the bottom and work your way up. For information on the University of Oregon's APA- and PCSAS-accredited clinical psychology PhD program, click [here](https://psychology.uoregon.edu/research/clinical-area).<br><br> Best of luck with the application process, and I genuinely look forward to reviewing your application! <br><br>
  
      filters:
        folders:
          - applicants
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: list
      # For Showcase view, flip alternate rows?
      #flip_alt_rows: false  


  - block: portfolio
    id: dei
    content:
      title: Commitment to Diversity, Equity, and Inclusion
      text: A core assumption in dialectical behavior therapy is that we are all doing the best we can and yet “people need to do better, try harder, and be more motivated for change” (Linehan, 2015). This dialectical perspective summarizes my approach to incorporating diversity, equity, and inclusion into my research, teaching, and mentoring. <br><br>I am committed to studying and preventing suicidal thoughts and behaviors and eating disorders among minoritized groups (particularly LGBTQIA+ groups through an intersectional lens), with the goal of reducing suicide and eating disorder inequities. Once I arrive at UO, I am committed to creating partnerships with people with lived experience of suicide and eating disorders, to ensure that the research I'm leading is aligned with the needs of the communities I'm intending to serve. <br><br>In my teaching and mentoring, I am committed to participating in and facilitating discussions about privilege, power, and oppression. I am further committed to translating conversations into actions to be better allies. <br><br>Diverse perspectives benefit the entire field of psychological science. As such, I believe that the field of psychology as a whole must do better to ensure the training of individuals with identities that have been historically excluded from the field (e.g., BIPOC, LGBTQIA+). <br><br>I am committed to always being the best ally I can, and always learning and practicing to be better.
      
      filters:
        folders:
          - dei
    design:
      columns: '1'
      view: list

  #- block: collection
  #  id: featured
  #  content:
  #    title: Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: false
  #  design:
  #    columns: '1'
  #    view: citation

  - block: accomplishments
    id: resources
    content:
      title: Resources
      subtitle: There is always help available. The resources below are available 24 hours a day, 7 days a week, 365 days a year.
      text: Dates refer to the date each resource was confirmed/updated.
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 'Suicide and Crisis Lifeline'
          certificate_url: ''
          date_end: ''
          date_start: '2023-08-01'
          description: ''
          organization: Call 988
          organization_url: ''
          url: ''
        - title: 'Crisis Text Line'
          certificate_url: ''
          date_end: ''
          date_start: '2023-08-01'
          description: ''
          organization:  Text PA to 741741
          organization_url: ''
          url: ''
        - title: 'Trevor Lifeline  (for LGBTQIA+ folks)'
          certificate_url: ''
          date_end: ''
          date_start: '2023-08-01'
          description: ''
          organization: 'Call 1-866-488-7386'
          organization_url: ''
          url: ''
        - title: 'Trans Lifeline'
          certificate_url: ''
          date_end: ''
          date_start: '2023-08-01'
          description: ''
          organization: 'Call 1-877-565-8860'
          organization_url: ''
          url: ''  
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
 

  - block: portfolio
    id: pets
    content:
      sort_ascending: true
      default_button_index: 0
      title: Lab Pets
      text: I am a proud mom to three senior pups. They are the loves of my life and a major source of my daily positive emotions. Click on the pictures to learn more about each pup. <br><br>I commit to regularly updating this page with students' pets, because who doesn't need more pictures of cute animals in their lives?!<br><br>
      filters:
        folders:
          - pets
    design:
      columns: '1'
      view: masonry

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: Lnf@uoregon.edu
    design:
      columns: '1'
      view: masonry



---
