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
    id: exp
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
        - title: Entrapeneur in Residence
          company: Tum Venture Lab
          company_logo: tumventure
          location: Munich
          date_start: '2025-01-01'
          description: |2-
              Entrepreneur in residence for an AI startup  for building an acceleration platform for improving the battery value chain @Tum Venture Lab.
        - title: Program Manager - Battery Technology Expert
          company: TUMInt Energy GmbH
          company_logo: tumint
          location: Munich
          date_start: '2025-01-01'
        - title: AI Research Scientist
          company: TUMInt Energy GmbH
          company_logo: tumint
          location: Munich
          date_start: '2025-01-01'
          date_end: '2025-03-01'
        - title: Data Scientist Research internship
          company: BASF AG
          company_url: 'https://www.basf.com/global/en.html'
          company_logo: basf
          location: Ludwigshafen
          date_start: '2023-01-01'
          date_end: '2023-05-31'
          description: |2-
              Responsibilities included:

              * Designing pipeline for electrochemical analysis of battery state-of-health and state-of-charge prognostics
              * Designing attention-based seq2seq models for battery lifetime prediction
              * Training using super-computer
    design:
      columns: '1'


  - block: experience
    id: edu
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Researcher in Data Science and AI for solid state battery electrolytes
          company: Technical University of Munich TUM
          company_url: 'https://www.crc.tum.de/crc/home/'
          company_logo: tum
          date_start: '2024-07-01'
        - title: PhD Data Science and Robotics - Summa Cum Laude
          company: Technical University of Munich TUM - Catalysis Research Center
          company_url: 'https://www.crc.tum.de/crc/home/'
          company_logo: tum
          date_start: '2024-01-01'
          date_end: '2024-06-30'
          description: |2-
            * Research Thesis: Design and Implementation of Enablers in Materials Acceleration Platforms for Battery Research [[Media TUM]](https://mediatum.ub.tum.de/1742765)
            * Led an international collaboration of laboratory automation integrating AIplanners, data analysis, management, and hardware orchestration
            * Supervision of numerous involved parties and budget requirements and successful contribution to financial grants application
            * Managed platform development, quality assessment, and deliverable coordination for BIG-MAP work packages
        - title: PhD candidate in Robotics and Automation Engineering
          company: Kahrlsrue Institute of technology
          company_url: 'https://www.kit.edu/'
          company_logo: kit
          date_start: '2020-01-01'
          date_end: '2023-12-31'
          description: |2-
            * Development of an automated materials acceleration platform as part of [Big Map](https://www.big-map.eu/)
            * Optimization of electrolyte formulations through active learning algorithms
            * Optimization of battery health prognostics through time series modelling
        - title: Master of Science in Artificial Intelligence - GPA 0.8 with distiction
          company: University of Huddersfield
          company_url: 'https://www.hud.ac.uk/'
          company_logo: hudd
          date_start: '2019-09-01'
          date_end: '2021-09-30'
          description: |2-
            * Thesis on Outlier treatment and efficient synthetic data generation for heart failure
            prediction.
            * **Chancellor's Prize** for Outstanding achivments by a postgraduate student
            * The Departmental **Prize for the Best Overall Performance** on Postgraduate study in Computer Science
            * The Departmental **Prize for the Best Postgraduate Project** in Computer Science
        - title: Master of Science in Biophysics - GPA 1.9 Good
          company: University Ulm
          company_url: 'https://www.uni-ulm.de/'
          company_logo: ulm
          date_start: '2018-09-01'
          date_end: '2019-03-30'
          description: |2-
            *  Functionalizing of cantilever in AFM for Biophysical applications
        - title: Master of Science in Advanced Materials - GPA 1.6 Good
          company: University Ulm
          company_url: 'https://www.uni-ulm.de/'
          company_logo: ulm
          date_start: '2016-11-01'
          date_end: '2019-06-30'
          description: |2-
            *  Functionalizing of cantilever in AFM for Biophysical applications
        - title: Bachelor of Engineering in Biomedical and Medical Engineering - GPA 16.90/20
          company: Amirkabir University of Technology - Teheran
          company_url: 'https://aut.ac.ir/en'
          company_logo: amkab
          date_start: '2016-11-01'
          date_end: '2019-06-30'
          description: |2-
            *  Synthesis and characterization of silver-doped in HA-akermanite nanocomposites
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: Python
          description: Favorite programming language for everything "Data" 🥇
          icon: python
          icon_pack: fab
        - name: Artificial Intelligence
          description: Machine Learning, Deep Learning, Reinforcement Learning, GenAI
          icon: brain
          icon_pack: fas
        - name: R
          description: Second favorite programming language 🥈
          icon: r-project
          icon_pack: fab
        # Empty space for centering the next one
        - name: SQL
          description: Database management and data manipulation
          icon: database
          icon_pack: fas
        - name: git/GitHub/GitLab
          description: Version control for all the coding projects
          icon: git
          icon_pack: fab
        - name: Data Science
          description: Computer Vision, Statistics, Data Engineering, Pipelines
          icon: chart-line
          icon_pack: fas

  # Publications
  - block: collection
    id: pub
    content:
      title: Recent Publications
      count: 5
      sort_by: 'Date'
      text: |2-
        ### List of all available publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '1'

  - block: markdown
    id: cert
    content:
      title: Certificates
      subtitle: A list of all my certificates
      text: |2-
        <div style="margin: 10px;">
          <div class="button-container">
            <div style="text-align: center;">
              {{< button relref="/udacity" >}}Udacity{{< /button >}}
              {{< button relref="/other" >}}Other Certificates{{< /button >}}
            </div>
          </div>
        </div>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: portfolio
    id: awd
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      filters:
        folders:
          - accomplishments
        exclude_featured: false
    design:
      columns: '1'



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
          tag: deeplearning
        - name: Data Analysis
          tag: dataanalysis
        - name: Laboratory Automation
          tag: labautomation
        - name: Feature Visualization
          tag: featurevis
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
---
