---
# Leave the homepage title empty to use the site title
title: 
date: 2025-07-29
type: landing

sections:
      #featured in banner  
  - block: markdown
    content:
      title: Liquid 3D
      subtitle: Financed by European Research Council (ERC) Consolidated Grant Liquid3D (Grant No. 101045072) under Horizon Europe (HORIZON) Program.
      text: | 
       Liquid3D proposes bioinspired electronics and machines that are soft, resilient, self-healing, shape-morphing, and fully recyclable. Functional sensing/acting/processing/energy cells will be 3D printed using a series of game changer Liquid Metal based composites.
       
       As a result, we will print futuristic soft electronics that sense and interact with humans or the environment. This provides an excellent design freedom to scientists for manufacturing complex “living” electronics, while guaranteeing that any possible product coming from these inventions will be Resilient, Repairable, and Recyclable. I expect that over 80% of microchips, and metals in the printed circuits, can be recovered. Liquid3D redefines the electronics, by rethinking the materials, fabrications, and design architectures. 
       
       These objectives are feasible, thanks to the recent breakthroughs that I made to the field: First; discovery of the biphasic (liquid-solid) composite based on Gallium-Indium Liquid Metal (LM), that allowed the first ever method for room temperature printing of stretchable circuits; and second, a method for inclusion of microelectronics into ultra-stretchable circuits through self-soldering, self-healing, and self-encapsulating of LM-Polymer composites. With Liquid3D I will develop fundamental understanding, and mathematical modelling of biphasic systems, and develops novel room temperature printable composites with sensing/acting/energy storage properties, and methods for recycling them. I will investigate novel forms of implementing truly 3D electronics, with distributed functional cells.
       
       Liquid3D intends to fundamentally rethink, the concept of electronics, as we know today. From rigid and brittle to soft, resilient and repairable; From polluting to recyclable; from battery dependent to self-powered; from 2D to truly 3D; It proposes a radically new way of making “greener” electronics. With Liquid3D I aim to establish the world leading centre on recyclable, and green electronics.
    design:
      columns: '1'
      spacing:
        padding: ['0px', '0', '0', '0']
        margin: ['0', '0', '0', '0']
         
  - block: markdown
    content:
      title:
      subtitle:
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: erc_logo.jpeg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain
          text_color_light: true
      spacing:
        padding: ['300px', '0', '50px', '0']

 
#Published articles
  - block: collection
    content:
      title: Liquid3d Published Articles
      text: 
      count: 100
      filters:
          folders: 
            - publication
          tag: 'liquid3d'
          
        
    design:
      view: compact
      columns: '1'
  
---