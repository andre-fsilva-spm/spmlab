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
            <a href="/liquid" style="background: transparent; color: white; padding: 15px 40px; border-radius: 8px; text-decoration: none; font-weight: 700; font-size: 1.1rem; border: 2px solid white; transition: background 0.3s ease;">
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
        padding: ['60px', '0', '60px', '0']
     
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

  # - block: markdown
  #   content:
  #     title: |
  #                 Mission
  #     subtitle: ''
  #     text: |
  #       <div style="text-align: center;">
  #         <p style="font-size: 1rem; margin-bottom: 0px;">
  #           The Soft and Printed Microelectronics Laboratory exists since 2016 to advance the field of stretchable electronics
  #         </p>
  #       </div>
  #   design:
  #     columns: '1'
  #     background:
  #       color: "aliceblue"
  #     spacing:
  #       padding: ["20px", "50px", "10px", "100px"]

  # - block: hero
  #   content:
  #     title: "Smart Materials"
  #     text: |
  #       Synthesis & Analysis of Metals, Polymers, 2D materials and Nano Particles that:
  #         <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 20px 0;">
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>✓Sense</li>
  #           <li>✓Actuate</li>
  #           <li>✓Conduct</li>
  #           <li>✓Store Energy</li>
  #         </ul>
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>✓Bend</li>
  #           <li>✓Stretch</li>
  #           <li>✓Heal</li>
  #           <li>✓Are Printable</li>
  #         </ul>
  #       </div>
  #     image:
  #       filename: MaterialSynthesis.png
  #   design:
  #     background:
  #       color: "aliceblue"
  #     css_class: "hero-image-left"
  #     spacing:
  #       padding: ["20px", "50px", "20px", "0"]

  # - block: hero
  #   content:
  #     title: "Fabrication Techniques"
  #     text: |
  #       <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 20px 0;">
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>✓3D Printing</li>
  #           <li>✓Inkjet Printing</li>
  #           <li>✓Extrusion Printing</li>
  #           <li>✓Surface Coating</li>
  #         </ul>
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>✓Laser Patterning</li>
  #           <li>✓Microchip soldering</li>
  #           <li>✓Custom Machines</li>
  #         </ul>
  #       </div>
  #     image:
  #       filename: tools.png
  #   design:
  #     background:
  #       color: "aliceblue"
  #     css_class: "hero-image-right"
  #     spacing:
  #       padding: ["0px", "50px", "20px", "0"]
  
  # - block: hero
  #   content:
  #     title: "Applications"
  #     text: |
  #       <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 20px 0;">
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>✓Energy Storage & Harvesting</li>
  #           <li>✓Smart Surfaces</li>
  #           <li>✓E-textiles</li>
  #           <li>✓Robotics</li>
  #         </ul>
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>✓Health:</li>
  #             <ul style="list-style-type: none; padding-left: 20px; margin-top: 5px;">
  #               <li>→Biomonitoring</li>
  #               <li>→Stimulation</li>
  #               <li>→Implants</li>
  #               <li>→Wearables</li>
  #             </ul>
  #         </ul>
  #       </div>
  #     image:
  #       filename: applications.png
  #   design:
  #     background:
  #       color: "aliceblue"
  #     css_class: "hero-image-left"
  #     css_style: |
  #       .hero-title { font-size: 15rem; }
  #       .hero-lead { font-size: 15rem; }
  #     spacing:
  #       padding: ["0px", "50px", "20px", "0"]
        
  # - block: hero
  #   content:
  #     title: "Sustainability & Responsible Electronics"
  #     text: |
  #       Work with the philosophy of the 3 Rs for electronics:
  #         <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 20px 0;">
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>♻ Reducing </li>
  #           <li>♻ Repairing</li>
  #           <li>♻ Recycling</li>
  #         </ul>
  #         <ul style="list-style-type: none; padding-left: 0;">
  #           <li>✓Biopolymers</li>
  #           <li>✓Biodegradable materials</li>
  #           <li>✓Reuse of Biowastes</li>
  #         </ul>
  #       </div>
  #     image:
  #       filename: recyclable.png
  #   design:
  #     background:
  #       color: "aliceblue"
  #     css_class: "hero-image-right"
  #     spacing:
  #       padding: ["0px", "50px", "20px", "0"]