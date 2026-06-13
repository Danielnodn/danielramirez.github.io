---
title: ""
summary: ""
date: "2026-01-05"
type: "landing"
sections:
  - block: "dev-hero"
    content:
      username: "me"
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I build"
        strings:
          - "data growth systems"
          - "ml marketing"
          - "dashboards"
          - "data pipelines"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: "View My Work"
          url: "#projects"
          icon: "arrow-down"
        - text: "Get In Touch"
          url: "#contact"
          icon: "envelope"
      bio: "Mexico City–based freelancer bridging data science and marketing. Junior Data Scientist with hands-on experience in ads management, UX design, and full marketing stack configuration. I turn data into growth strategies and build systems that actually work."
    design:
      style: "centered"
      avatar_shape: "circle"
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding:
          - "6rem"
          - "0"
          - "4rem"
          - "0"
    ce: "section-hero"
    id: "hero"
    As: "section-f40954b1"
  - block: "portfolio"
    content:
      title: "Featured Projects"
      subtitle: "A selection of my recent work"
      count: 0
      filters:
        folders:
          - "projects"
      buttons:
        - name: "All"
          tag: "*"
        - name: "Digital Strategy"
          tag: "Digital Strategy"
        - name: "UX/UI"
          tag: "UX/UI"
        - name: "E-commerce"
          tag: "E-commerce"
      default_button_index: 0
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "4rem"
          - "0"
    ce: "section-projects"
    id: "projects"
    As: "section-c4dfe947"
  - block: "tech-stack"
    content:
      title: "Tech Stack"
      subtitle: "Technologies I use to build things"
      categories:
        - name: "Languages"
          items:
            - name: "TypeScript"
              icon: "devicon/typescript"
            - name: "JavaScript"
              icon: "devicon/javascript"
            - name: "Python"
              icon: "devicon/python"
            - name: "Go"
              icon: "devicon/go"
        - name: "Frontend"
          items:
            - name: "React"
              icon: "devicon/react"
            - name: "Next.js"
              icon: "devicon/nextjs"
            - name: "Tailwind CSS"
              icon: "devicon/tailwindcss"
            - name: "Alpine.js"
              icon: "devicon/alpinejs"
        - name: "Backend"
          items:
            - name: "Node.js"
              icon: "devicon/nodejs"
            - name: "Express"
              icon: "devicon/express"
            - name: "PostgreSQL"
              icon: "devicon/postgresql"
            - name: "Redis"
              icon: "devicon/redis"
        - name: "DevOps"
          items:
            - name: "Docker"
              icon: "devicon/docker"
            - name: "AWS"
              icon: "devicon/amazonwebservices"
            - name: "GitHub Actions"
              icon: "brands/github"
            - name: "Vercel"
              icon: "devicon/vercel"
    design:
      style: "grid"
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "4rem"
          - "0"
    ce: "section-skills"
    id: "skills"
    As: "section-def3e4d8"
  - block: "resume-experience"
    content:
      title: "Experience"
      date_format: "Jan 2006"
      items:
        - title: "Senior Software Engineer"
          company: "Tech Corp"
          company_url: ""
          company_logo: ""
          location: "San Francisco, CA"
          date_start: "2023-01-01"
          date_end: ""
          description: |-
            * Lead development of microservices architecture serving 1M+ users
            * Improved API response time by 40% through optimization
            * Mentored team of 5 junior developers
            * Tech stack: React, Node.js, PostgreSQL, AWS
        - title: "Full-Stack Developer"
          company: "Startup Inc"
          company_url: ""
          company_logo: ""
          location: "Remote"
          date_start: "2021-06-01"
          date_end: "2022-12-31"
          description: |-
            * Built and deployed 3 production applications from scratch
            * Implemented CI/CD pipeline reducing deployment time by 60%
            * Collaborated with design team on UI/UX improvements
            * Tech stack: Next.js, Express, MongoDB, Docker
        - title: "Junior Developer"
          company: "Web Agency"
          company_url: ""
          company_logo: ""
          location: "New York, NY"
          date_start: "2020-01-01"
          date_end: "2021-05-31"
          description: |-
            * Developed client websites using modern web technologies
            * Maintained and updated legacy codebases
            * Participated in code reviews and agile ceremonies
            * Tech stack: React, WordPress, PHP, MySQL
    design:
      columns: "1"
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "4rem"
          - "0"
      is_education_first: false
    ce: "section-experience"
    id: "experience"
    As: "section-69e59b05"
      # - block: "collection"
  #   content:
  #     title: "Recent Posts"
  #     subtitle: "Thoughts on web development, tech, and more"
  #     text: ""
  #     filters:
  #       folders:
  #         - "blog"
  #       exclude_featured: false
  #     count: 3
  #     order: "desc"
  #   design:
  #     view: "card"
  #     columns: 3
  #     background:
  #       color:
  #         light: "#f5f5f5"
  #         dark: "#08080c"
  #     spacing:
  #       padding:
  #         - "4rem"
  #         - "0"
  #         - "4rem"
  #         - "0"
  #   ce: "section-blog"
  #   id: "blog"
  #   As: "section-988e59c5"
  - block: "contact-info"
    content:
      title: "Get In Touch"
      subtitle: "Let's build something amazing together"
      text: |-
        I'm always interested in hearing about new projects and opportunities.
        Whether you're looking to hire, collaborate. Feel free to reach out!
      email: "daniel.ramirezup@gmail.com"
      autolink: true
    design:
      columns: "1"
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "4rem"
          - "0"
    ce: "section-contact"
    id: "contact"
    As: "section-853fb753"
  - block: "cta-card"
    content:
      title: "Open to Opportunities"
      text: |-
        I'm currently looking for **senior engineering** or **tech lead** roles.

        Let's connect and discuss how I can help your team.
      button:
        text: "Download Resume"
        url: "uploads/resume.pdf"
        new_tab: true
    design:
      card:
        css_class: "bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700"
        text_color: "dark"
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "6rem"
          - "0"
    ce: "section-79a174d1"
    As: "section-9331708a"
---
