---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Contact
subtitle:

content:
  # # Automatically link email and phone or display as text?
  # autolink: true

  # # Email form provider
  # form:
  #   provider: netlify
  #   formspree:
  #     id:
  #   netlify:
  #     # Enable CAPTCHA challenge to reduce spam?
  #     captcha: false

  # Contact details (edit or remove options as required)
  # email: test@example.org
  # phone: 888 888 88 88
  address:
    street: Av. Lib. Bernardo O'Higgins 611
    city: Rancagua
    region: Región de O'Higgins
    # postcode: '94305'
    country: Chile
    country_code: CL
  coordinates:
    latitude: '-34.1646'
    longitude: '-70.74170'
  directions: Building B, Floor 5th
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me in Twitter
      link: 'https://twitter.com/raulrainfall'
    # - icon: researchgate
    #   icon_pack: fas
    #   name: Research Gate
    #   link: 'https://zoom.com'      

design:
  columns: '2'
---
