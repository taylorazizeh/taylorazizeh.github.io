---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: taylor-azizeh
  - block: markdown
    #id: about   
    content:
      default_button_index: 0
      title: ""
      subtitle: ''
      #text: >-

      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      
    design:
      background:
        #color: '#1f4e74'
        text_color_light: false
        image:
          filename: slider/iceland.jpg
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.75
        image:
          filename: slider/sermitsiaq.jpg
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.75
        image:
          filename: slider/weddell.JPG
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.75
      spacing:
        padding: ["150px", "0", "70px", "0"]  
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  #- block: slider
    #content:
      #title: 
      #align: center
      #background:
        #position: right
        #color: '#666'
        #brightness: 0.7
        #media: iceland.jpg
        #fit: cover
      #title: Lunch & Learn ☕️
      #content: 'Share your knowledge with the group and explore exciting new topics together!'
      #align: left
      #background:
        #position: center
        #color: '#555'
        #brightness: 0.7
        #media: background.JPG
        #fit: cover
      #title: World-Class Semiconductor Lab
      #content: 'Just opened last month!'
      #align: right
      #background:
        #position: center
        #color: '#333'
        #brightness: 0.5
        #media: icon.png
        #fit: cover
  - block: experience
    id: experience
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
        - title: Aerial Observer
          company: Upwell
          company_url: 'https://www.upwell.org/'
          company_logo: UpwellHorizontal
          location: Monterey, California
          date_start: '2023-05-01'
          date_end: ''
        - title: Protected Species Observer
          company: Elkhorn Slough National Estuarine Research (ESNERR)
          company_url: 'https://elkhornslough.org/reserve/'
          company_logo: ESF_logo
          location: Moss Landing, California
          date_start: '2022-05-01'
          date_end: ''
          description: Help protect federally protected marine species through monitoring and mitigation.
        - title: Naturalist and Deckhand
          company: Sea Goddess Whale Watching
          company_url: 'https://seagoddesswhalewatch.com/'
          company_logo: SGWW_logo
          location: Moss Landing, California
          date_start: '2022-03-01'
          date_end: ''
          description: Assist with safe operation of vessel around marine mammals, conduct outreach with customers, and help identify species at distance.
        - title: Graduate Student
          company: Moss Landing Marine Laboratories
          company_url: 'https://mlml.sjsu.edu/birdmam/taylor-azizeh'
          company_logo: mlml-logo
          location: Moss Landing, California
          date_start: '2021-08-01'
          date_end: ''
          description: Currently a graduate student in the Vertebrate Ecology Lab, studying the foraging ecology of emperor penguins.
        - title: Research Intern
          company: British Antarctic Survey
          company_url: 'https://www.bas.ac.uk/'
          company_logo: bas_logo
          location: Cambridge, United Kingdom
          date_start: '2020-08-01'
          date_end: '2021-05-01'
          description: Worked on a project with Dr. Jennifer Jackson examining historical southern right whale catch data.
        - title: Field Officer
          company: Oceanomare Delphis Onlus
          company_url: 'https://oceanomaredelphis.org/en/'
          company_logo: ODO_logo
          location: Ischia, Italy
          date_start: '2020-06-01'
          date_end: '2020-09-01'
          description: Assist with acoustic and behavioral surveys of cetaceans (namely sperm whales) on the R.V. Jean Gab in the Tyrrhenian Sea.
        - title: Open Study/Research Student
          company: U.S. Fulbright Program
          company_url: 'https://us.fulbrightonline.org/'
          company_logo: fulbright_logo
          location: Aarhus, Denmark | Nuuk, Greenland
          date_start: '2019-08-01'
          date_end: '2020-07-01'
          description:
        - title: International Research Experience for Students (IRES) Participant
          company: National Science Foundation
          company_url: 'https://new.nsf.gov/funding/opportunities/international-research-experiences-students-ires-0'
          company_logo: NSF_logo
          location: Loja, Ecuador
          date_start: '2018-01-01'
          date_end: '2018-12-01'
          description: Participated in the IRES Program at the University of Idaho, investigating bat physiology in an urbanized landscape with Dr. Lisette Waits and Dr. Rodrigo Cisneros.
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
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards, Scholarships, & Grants'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2023-05-01'
          description: ''
          organization: Moss Landing Marine Laboratories
          organization_url: 
          title: 'Justice, Equity, Diversity, and Inclusion (JEDI) Scholarship'
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2022-08-01'
          description: 
          organization: Society of Marine Mammals
          organization_url: https://marinemammalscience.org/
          title: 'Best Student Presentation Regional Award (South America)'
          url: 
        - certificate_url: 
          date_end: ''
          date_start: '2022-09-01'
          description: ''
          organization: California State University
          organization_url: https://www.calstate.edu/impact-of-the-csu/research/csuperb
          title: 'CSU Program for Education & Research in Biotechnology Grant'
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2022-05-01'
          description: ''
          organization: Moss Landing Marine Laboratories
          organization_url: 
          title: 'Wave Scholarship'
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-12-01'
          description: ''
          organization: CSU Council on Ocean Affairs, Science, and Technology (COAST)
          organization_url: https://www.calstate.edu/impact-of-the-csu/research/coast/Pages/default.aspx
          title: 'COAST Graduate Student Research Award Program'
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-09-01'
          description: ''
          organization: San José State University
          organization_url: 
          title: 'Viola Palmer Memorial Scholarship'
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-09-01'
          description: ''
          organization: Kirsten Scott Memorial Trust
          organization_url: http://www.kirstenscottmemorialtrust.com/
          title: 'Kirsten Scott Memorial Trust Research Grant'
          url: ''          
        - certificate_url: 
          date_end: ''
          date_start: '2019-03-01'
          description: ''
          organization: University of Idaho
          organization_url: https://www.uidaho.edu/cnr
          title: 'Outstanding Environmental Science Senior Undergraduate'
          url: 'https://www.uidaho.edu/-/media/UIdaho-Responsive/Files/cnr/about/cnr-awards-2018-2019.pdf'        
        - certificate_url: 
          date_end: ''
          date_start: '2018-10-01'
          description: ''
          organization: University of Idaho
          organization_url: https://www.uidaho.edu/cnr
          title: 'Alumni Excellence Award'
          url: ''    
    design:
      columns: '2'
      background:
        image:
          # Name of image in `assets/media/`.
          filename: background.jpeg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.6
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  - block: markdown
    id: photography
    content:
      title: Photography
      subtitle: ''
      text: |-
        {{< gallery album="photography" >}}
    design:
      columns: '1'
  - block: collection
    id: outreach
    content:
      title: Past & Current Outreach
      subtitle: ''
      text: 'XX'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - outreach
        author: ""
        category: ""
        tag: ""
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: taylorazizeh@gmail.com
      phone: 
      address:
        street: 8272 Moss Landing Road
        city: Moss Landing
        region: CA
        postcode: '95039'
        country: United States
        country_code: US
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/TAzizeh'
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '36.7944'
        longitude: '-121.7877'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      justify-content: center
      background:
        image:
          # Name of image in `assets/media/`.
          filename: iceland.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.6
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
---
