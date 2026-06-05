---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: View CV
        url: uploads/resume.pdf
      headings:
        about: 'Bio'
        education: 'Education'
        interests: 'Topics'
    design:
      # Apply a gradient background
      # css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
 
  # - block: collection
  #   id: pub
  #   content:
  #     title: Recent Papers
  #     text: ''
  #     filters:
  #       folders:
  #         - publications
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: collection
    id: projs
    content:
      title: Recent Projects
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      view: article-grid
      columns: 3
  - block: markdown 
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        <div style="max-width: 680px; margin: 0 auto; font-size: 1.2rem;">

        Lize's core research focus is person-centred human-AI interaction design, originally developed in her doctoral thesis. More than minimising ethical violations or enhancing usability, this approach - inspired by person-centred care in biomedical ethics - aims to treat individuals as whole persons with complex, evolving needs and long-term goals, and asks how AI systems can be designed to genuinely support those goals while preserving and strengthening human agency.

        Her current work spans three connected areas: personalising LLM-based dialogue agents for behavioural support; the design of behaviour change technologies that foster autonomous, lasting motivation rather than engagement-driven dependency; and the implications of generative AI writing tools for academic skill development. A consistent concern is how to support users agency and integration in how they spend their time and attention.
        </div>
  - block: markdown 
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
  
        <div style="max-width: 680px; margin: 0 auto; font-size: 1.2rem;">
        <p>Lize co-designed and coordinates three courses in the VU's BSc Artificial Intelligence programme.</p>
        </div>

        <div class="course">
        <div style="max-width: 680px; margin: 0 auto; font-size: 1.2rem;">
          <p><b>Modelling Human Behaviour</b> integrates perspectives from cognitive science, behavioural psychology, social network analysis, and computational modelling to give students a strong interdisciplinary foundation for understanding and modelling human behaviour. It covers the full model development pipeline - from the theoretical and ethical frameworks that underpin why and how we model behaviour, to practical implementation across multiple modelling tools and methods, including agent-based modelling in NetLogo, social network analysis in Python, and behavioural design principles for digital platforms. Students engage critically with the strengths, limitations, and risks of contemporary approaches to predicting and influencing behaviour, and consider the implications of applying these in AI and computing systems.</p>
        </div>

        <div class="course">
        <div style="max-width: 680px; margin: 0 auto; font-size: 1.2rem;">
          <p><b>Research Design for AI</b> guides students through the full research cycle of their final thesis project: formulating research questions, conducting literature reviews, selecting appropriate methodologies, handling data ethically, and communicating findings clearly and critically. The course runs alongside the BSc AI Project, supporting students with the timely and succesful completion of each thesis milestone.</p>
        </div>

        <div class="course">
        <div style="max-width: 680px; margin: 0 auto; font-size: 1.2rem;">
          <p><b>Project Socially Aware Computing</b> is a project-based course in which students conduct independent research to build, analyse, and critically report on an agent-based simulation of phenomenon involving social interaction in the NetLogo environment.</p>
        </div>
  
  
  - block: markdown 
    id: vision
    content:
      title: 'Mission Statement'
      subtitle: ''
      text: |-
        <div style="max-width: 680px; margin: 0 auto; font-size: 1.2rem;">
        My research approach is human-centred in that it starts with identifying specific problems from users' own perspectives, before trying to find the most effective and responsible ways to address them, rather than starting with a tool and trying to find ways to utilise it. I am constantly seeking to challenge my existing views and assumptions by reading broadly and learning new techniques to find the most appropriate and ethical routes to addressing the issues I care about. My aim is to maximise the benefits of AI and digitisation while minimising unnecessary technological dependence and unintended risks. To do so, I integrate psychological theory and critical, big-picture thinking with mixed methods user studies, and theory-driven interaction design. 
        </div>


  
        
  #   design:
  #     columns: '1' 
  #     css_style: 'font-size: 2rem;' 


  # - block: collection
  #   id: papers
  #   content:
  #     title: Projects & Affiliations
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 3  

  # - block: resume-skills
  # - block: collection
  #   id: talks
  #   content:
  #     title: Talks & Courses
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: resume-experience
  #   id: detailed-ed
  #   content:
  #     username: admin
  #   design:
  #     # Hugo date format
  #     date_format: 'January 2006'
  #     # Education or Experience section first?
  #     is_education_first: false
    
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  #   design:
  #     show_skill_percentage: false
  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: admin
  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: admin
  # - block: markdown 
  #   id: hobbies
  #   content:
  #     title: 'Hobbies & Personal Life'
  #     subtitle: ''
  #     text: |-
  #       I am 

  #       <ul>
  #         <li>Coffee</li>
  #         <li>Tea</li>
  #         <li>Milk</li>
  #       </ul>
  #   design:
  #     columns: '1' 

  # # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!

  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: 'bg-primary-300'
  #       css_style: ''
---
