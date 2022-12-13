---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:


content:
  # Automatically link email and phone or display as text?
  autolink: true
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true
    #netlify:
      # Enable CAPTCHA challenge to reduce spam?
      #captcha: true
    contact_links:
      - icon: github
        icon_pack: fab
        name: Find us on GitHub
        link: https://github.com/CrossMoDA/
      - icon: vimeo
        icon_pack: fab
        name: Find us on Vimeo
        link: 'https://vimeo.com/user151973995'

design:
  columns: '2'
  #color: "rgb(226, 226, 226)"
  background:
    text_color_light: true
    color-background: "#fff"
    #background-color: "#fff"
---
