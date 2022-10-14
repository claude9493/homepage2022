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
  email: yzhangjy@connect.ust.hk
  phone: (852) 5483 1981
  address:
    street: 1st Duxue Road, Nansha District
    city: Guangzhou
    region: Guangdong
    # postcode: '94305'
    country: China
    country_code: CN
  coordinates:
    latitude: '22.90042099101432'
    longitude: '113.44213759899807'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    # - icon: twitter
    #   icon_pack: fab
    #   name: DM Me
    #   link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Invitation Link
      link: 'https://hkust.zoom.us/j/3159733278'

design:
  columns: '2'
---
