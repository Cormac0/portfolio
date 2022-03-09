---
# An instance of the Contact widget.
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
      captcha: false

  # Contact details (edit or remove options as required)
  email:
  phone: 
  address:
    street: 1-007, 77 Massachusetts Ave
    city: Cambridge
    region: MA
    postcode: '02139'
    country: United States
    country_code: US
  coordinates:
    latitude: 
    longitude: 
  directions: 
  office_hours:
  appointment_url:
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: DM Me
      link: 'https://www.linkedin.com/in/cormac-o-neill/'

design:
  columns: '2'
---
