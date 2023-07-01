---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Quantum Beginners Initiative
      image:
        filename: welcome.jpg
      text: |
        <br>

        The **Quantum Beginners** is an initiative part of QIndia. It consists of blog posts and tutorial series focused on helping Quantum beginners find their footing. There are many resources out there for people to learn about quantum computing. However we would like to create a place where absolute beginners can start from, like a “start here” section that then takes them step-by-step through the process of understanding the minimum before exploring the world of quantum computing for themselves. The content will be a combination of original creations by the team and links to specific sections of already existing content
  
  - block: collection
    content:
      title: Latest News
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
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        Welcome to Quantum beginners initiative 
    design:
      columns: '1'
---
