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
        - title: Data Scientists Research internship
          company: BASF AG
          company_url: 'https://www.basf.com/global/en.html'
          company_logo: basf
          location: Ludwigshafen
          date_start: '2023-01-01'
          date_end: '2023-03-31'
          description: |2-
              Responsibilities include:

              * Analysing a big data system on battery formulation
              * Designing and training  LSTM Model for battery formulation prediction ond the "quriosity" super computer 
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
        - title: PhD in Robotics and Automation Engineering
          company: Kahrlsrue Institute of technology
          company_url: 'https://www.kit.edu/'
          company_logo: kit
          date_start: '2020-01-01'
          date_end: ''
          description: |2-
            * Development of an automated material acceleration platform as part of [Big Map](https://www.big-map.eu/)
            * Optimization of electrolyte formulations through active learning algorithms
        - title: Master of Science in Artificial Intelligence - GPA 0.8 with distiction
          company: University of Huddersfield
          company_url: 'https://www.hud.ac.uk/'
          company_logo: hudd
          date_start: '2019-09-01'
          date_end: '2019-09-30'
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
          date_end: '2019-06-30'
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
        - title: Bachelor of Science in Biomedical and Mediacal Engeneering - GPA 16.90/20
          company: Amirkabir University of Technology - Teheran
          company_url: 'https://aut.ac.ir/en'
          company_logo: amkab
          date_start: '2016-11-01'
          date_end: '2019-06-30'
          description: |2-
            *  Functionalizing of cantilever in AFM for Biophysical applications
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: Python
          description: Favourite programming language for everything "Data" 🥇
          icon: python
          icon_pack: fab
        - name: Artificial Intelligence
          description: Machine learning, deep learning, reinforcment learning and data visualization📊
          icon: brain
          icon_pack: fas
        - name: R
          description: Second favourite programming language 🥈
          icon: r-project
          icon_pack: fab
        # Empty space for centering the next one
        - name:
          description:
          icon:
          icon_pack:
        - name: git/GitHub/GitLab
          description: Version control for all the coding projects
          icon: git
          icon_pack: fab

  # Publications
  - block: collection
    id: pub
    content:
      title: Recent Publications
      text: |2-
        ### List of all my publicly available publications
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
      subtitle: A (incomplete) list of all my certificates
      text: |2-
        <div style="margin: 10px;">
          <div class="button-container">
            <div style="text-align: center;">
              {{< button relref="/udacity" >}}Udacity{{< /button >}}
              {{< button relref="/udacity" >}}Other Certificates{{< /button >}}
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
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/fuzhanrahmanian'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
