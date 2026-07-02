---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

active: true

# Order that this section appears on the page.
weight: 70

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  # Kept false so the raw email address is not emitted into the page HTML; a clickable
  # mailto link is assembled client-side (see layouts/partials/hooks/head-end/email-link.html).
  autolink: false

  # Email form provider
  #form:
    #provider: netlify
    #netlify:
      # Enable CAPTCHA challenge to reduce spam?
      #captcha: false

  # Contact details (edit or remove options as required)
  # No-JavaScript fallback only (obfuscated, no "@"). JavaScript upgrades this to a real
  # clickable mailto link so the plain address is never present in the served HTML.
  email: "raul.duarte 'at' yale.edu"
  #phone:
  address:
    street: 30 Hillhouse Avenue
    city: New Haven
    region: CT
    postcode: '06511'
    country: United States
    country_code: US
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://x.com/rduartegonzalez'
design:
  columns: '2'
---
