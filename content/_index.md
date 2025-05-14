---
title: "Welcome" # Title for the browser tab and search engines
# Toha specific front matter for homepage layout
layout: "home" # Specifies to use the Toha home layout

# Intro Section
intro:
  enable: true
  title: "Hi, I'm Husain" # Replace [Your Name]
  subtitle: "Cloud Architect | AWS | Kubernetes | Terraform | Python"
  content: |
    I am a passionate and experienced Cloud Architect with over 5 years of expertise in designing, implementing, and managing robust cloud solutions.
    My core skills revolve around AWS, Kubernetes, Terraform, and Python, enabling me to build scalable, secure, and cost-effective infrastructure.
    Explore my site to learn more about my work, projects, and thoughts on cloud technologies.
  # Optional: Image for the intro section (e.g., your photo or a relevant graphic)
  # image: "/images/home-intro.jpg" # Place in static/images/
  # buttons:
  #   - label: "View My Work"
  #     url: "/work/"
  #     style: "primary" # or "secondary"
  #   - label: "Read My Blog"
  #     url: "/posts/"
  #     style: "secondary"

# Sections to display on the homepage.
# Toha theme allows you to enable/disable and order sections.
# The `features` and `recentPosts` sections are configured in `config.yaml`
# and will be displayed if enabled there.

# You can add custom sections here if needed, following Toha's documentation.
# For example, a section about your services or a call to action.

# Example of enabling a section directly in front matter (if supported by Toha for _index.md)
# sections:
#  - type: about # This would typically pull content from content/about.md or a partial
#    enable: true
#  - type: experiences # This would pull from content/experiences/*
#    enable: true
#  - type: projects # This would pull from content/projects/*
#    enable: true
#  - type: recent_posts
#    enable: true
#  - type: contact
#    enable: true

# Note: The Toha theme often uses `config.yaml` for controlling homepage sections
# like 'features' and 'recentPosts'. The `sections` array above is a more
# generic Hugo approach that Toha might also support or have its own way to define.
# Refer to Toha documentation for the most accurate way to customize homepage sections.
---

