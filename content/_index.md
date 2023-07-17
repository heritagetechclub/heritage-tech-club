---
# Leave the homepage title empty to use the site title
title:
date: 2023-07-16
type: landing

sections:
  - block: hero
    content:
      title: |
        Heritage
        Technology Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Heritage Technology Club** is an alumni and student-led club at Heritage Institute of Technology. The goal is of the club to educate the student community about the technology industry and to support and provide resources to HIT students pursuing careers in this industry. By helping build the tech community within Heritage, the HTC aims to create a long-lasting community for its members.
  
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

---