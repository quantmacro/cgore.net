---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact
active: true  # Activate this widget? true/false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  text: |-
    For questions about the research on this site, or to discuss collaboration, email is best.

  # Contact details are read from this block in Wowchemy v5, not from params.yaml.
  email: christina.gore@nist.gov
  address:
    street: 100 Bureau Drive
    city: Gaithersburg
    region: MD
    postcode: '20899'
    country: United States
    country_code: US
  directions: Applied Economics Office, National Institute of Standards and Technology

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

design:
  columns: '2'
---
