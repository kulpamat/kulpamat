---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: For any questions or appointments please reach out through this contact forum or one of my listed points of contact

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
  email: kulpamat@gmail.com
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Follow or DM Me
      link: 'https://twitter.com/mooseofluv'


design:
  columns: '2'
---
