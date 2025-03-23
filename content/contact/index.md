---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We want to hear from you!
      email: f.Ying@massey.ac.nz
      phone: +64 92136218
      address:
        street: 20 Symonds Street, Auckland Central, Auckland 1010
        city: Auckland Central
        region: Auckland
        postcode: '1010'
        country: New Zealand
        country_code: NZ
      coordinates:
        latitude: '-36.85285'
        longitude: '174.77011'
      directions: Enter Building X and take the stairs to Office XXX on Floor X
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://advancedwood.github.io/benz-website/'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
