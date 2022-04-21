---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: NeuroHSI team
active: true

content:
  # Automatically link email and phone or display as text?
  autolink: true
  contact_links:
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: xjvlwdwb
    #netlify:
      # Enable CAPTCHA challenge to reduce spam?
      #captcha: true

  # Contact details (edit or remove options as required)
  #email: test@example.org
  #phone: 888 888 88 88
  address:
    street: 1 Lambeth Palace Road
    city: London
    region: ''
    postcode: SE1 7EU, UK
    country: United Kingdom
    country_code: GB
  #coordinates:
  #  latitude: '51.49973264645856'
  #  longitude: '-0.11626826208690387'
  directions: Becket House 9th floor
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: github
  #    icon_pack: fab
  #    name: Find us on GitHub
  #    link: https://github.com/cai4cai
  #  - icon: vimeo
  #    icon_pack: fab
  #    name: Find us on Vimeo
  #    link: 'https://vimeo.com/cai4cai'
  
design:
  columns: '2'
---
