---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        MetaVis
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **MetaVis** has been a company of excellence for Industrial Artificial Intelligence research, providing solutions to industrial anomaly detection since its founding in 2021.
  
  - block: collection
    content:
      title: Projects
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: project
    design:
      view: card
      columns: '1'
 
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./project/" cta_text="See our projects →" %}}
    design:
      columns: '1'

---