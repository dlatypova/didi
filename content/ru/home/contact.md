---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Контакты
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
  email: 1032215005@pfur.ru
  phone: 000 000 00 00
  address:
    street: 
    city: Москва
    region: РУДН
    postcode: ''
    country: Россия
    country_code: RU
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Где-то
  office_hours:
    - 'Понедельник-Пятница с 13:00 до 15:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
