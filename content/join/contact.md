---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Contact

content:
  # Contact (edit or remove options as required)

  email: georgios.bouloukakis@telecom-sudparis.eu
  phone: 0033 6 52 47 10 86
  address:
    street: 9 Rue Charles Fourier
    city: Évry-Courcouronnes
    region: Île-de-France
    postcode: '91000'
    country: France
    country_code: FR
  coordinates:
    longitude: '2.443393315594366'
    latitude: '48.625245547208046'
  directions: Enter Building E and take the the elevator to Office 304 on Floor 3
  office_hours:
    - 'Monday ______ to ____ '
    - 'Wednesday ________ to _____ '

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
  columns: '1'
---