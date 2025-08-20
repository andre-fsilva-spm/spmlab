---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 
        content:
        align: center
        background:
          image:
            filename: SmartMaterials.png
            size: cover
            text_color_light: true
          position: center
          color: '#666'
      - title: 
        content:
        align: center
        background:
          image:
            filename: FabricationTechnqiques.png
            size: cover
            text_color_light: true
          position: center
          color: '#666'
      - title: 
        content:
        align: center
        background:
          image:
            filename: applications_banner.png
            size: cover
            text_color_light: true
          position: center
          color: '#666'
      - title: 
        content:
        align: center
        background:
          image:
            filename: sustainability.png
            size: cover
            text_color_light: true
          position: center
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: 800px
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000 
  
#ERC Funding
  - block: markdown
    id: simple-cta
    content:
      title: ERC Funding
      text: |
        <div style="text-align: center; margin: 40px 0;">
          <p style="font-size: 1.2rem; margin-bottom: 30px; color: white;">
            The SPM lab is funded by ERC Project Liquid 3D 🇪🇺
          </p>
            <a href="./liquid/" style="background: transparent; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 1.1rem; border: 2px solid white; transition: background 0.3s ease;">
              Learn More
            </a>
          </div>
        </div>
    design:
      columns: '1'
      background:
        color: "#19323C"
        text_color_light: true
      spacing:
        padding: ['30px', '0', '30px', '0']
  
 #Featured articles
  - block: collection
    content:
      title: Featured Articles
      text: 
      count: 5
      filters:
        folders:
          - publication
        tag: 'featured'
        
    design:
      view: article-grid
      columns: '1'


 #Multidisciplinary Team
  - block: hero
    id: team_banner
    content:
      title: 
      text: |
        <div style="text-align: center; margin: 40px 0;">
          <p style="font-size: 1.2rem; margin-bottom: 30px; color: white;">
            A Lab with experts from different fields
          </p>
        </div>
        <div style="text-align: center; margin: 40px 0;">
        <a href="./people/" style="background: transparent; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 1.1rem; border: 2px solid white; transition: background 0.3s ease;">
              Meet the team
            </a>
        </div>
      image:
        filename: team_banner.jpg
    design:
      background:
        color: "#19323C"
        text_color_light: true
      spacing:
        padding: ['50px', '0', '30px', '0']

 #Latest News section
  - block: collection
    content:
      title: Latest News 
      subtitle:
      text: 
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '1'
      spacing:
        padding: ['60px', '0', '10px', '0']

#Research Areas Section
  - block: portfolio
    id: research
    content:
      title: Research Areas
      text: |
       <div style="text-align: center; margin: 0px 0;">
       Stretchable electronics is a multidisciplinary field, and we tackle different problems. Find out more about or research areas.
       </div> 
      filters:
        folders:
          - research
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
    design:
      columns: '1'
      view: masonry
      flip_alt_rows: false
      spacing:
        padding: ['60px', '0', '10px', '0']
 

  #Published articles
  - block: collection
    content:
      title: Latest Published Articles
      text: 
      count: 3
      filters:
        folders:
          - publication
        
        
    design:
      view: compact
      columns: '1'
    #featured in banner  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div style="text-align: center; margin: 0px 0;">
          <p style="font-size: 1.2rem; margin-bottom: 0px;">
            Featured In ✨
          </p>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0px', '0', '0', '0']
        margin: ['0', '0', '0', '0']
      background:
        color: #f7f7f7    
  - block: markdown
    content:
      title:
      subtitle:
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: featured_banner.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: actual
          text_color_light: true
      spacing:
        padding: ['90px', '0', '50px', '0']

#Banner meet team and instagram
  - block: markdown
    content:
      title:
      subtitle: 
      text: |
        <div style="text-align: center; margin: 40px 0;">
            <a href="./people/" style="background: transparent; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 1.1rem; border: 2px solid white; transition: background 0.3s ease;">
              Meet the team
            </a>
        </div>
        <div>
        <center>            
            <a href="https://www.instagram.com/softprintedmicro/" style="background: transparent; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 1.1rem; border: 2px solid white; transition: background 0.3s ease;">
              Follow us on Instagram 📸: @️softprintedmicro
            </a>
        </center>
        <br>        
        <center>#StretchableElectronics &nbsp; #PrintedElectronics  &nbsp; #LiquidMetals  &nbsp; #ElectronicTattoos &nbsp; #PressureMappingFilms  &nbsp; #SmartTextiles</center>
        </div>
    design:
      columns: '1'
      background:
        color: "#19323C"
        gradient_angle: 45
        text_color_light: true
    spacing:
        padding: ['0px', '0', '0px', '0']

---