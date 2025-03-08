---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image: 
          # Add your image background to `assets/media/`.
          filename: bg1.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
        # Card background color (CSS class)
        css_class: "bg-primary-700"
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      skill_hover: true
      show_skill_percentage: true  
      css_class: dark
      background:
        color: black
      text_color_light: true
        #image:
        #  filename: bg1.svg
      filters:
        brightness: 1.0
        size: cover
        position: center
        parallax: true
        parallax_speed: 0.8
        class: "bg-primary-700"
          

---
