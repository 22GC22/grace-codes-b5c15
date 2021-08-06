---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m Garima!'
    subtitle: ' I am a developer who is figuring things out as she goes! You can contact me for front end website designing and python projects. I''ll help you in anyway I can!'
    actions:
      - label: Contact Me
        url: /contact
        style: primary
    image: /images/GC.png
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: New Posts
    features:
      - title: 5 reasons why you can't hep but LOVE python
        subtitle: "Python, our very own Slytherin\_of programming languages."
        content: "We all love python to a certain degree and the language doesn't\_let us down either. It's simplicity is flawless and shortness of the codes garners everyone's attention towards it like *\"Hey, look at that!\"*, am I right? But what makes it so great? Lets talk about it in detail.\n"
        actions:
          - label: Continue Reading
            url: /blog/5-reasons-python
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/python.png
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: form_section
    content: >
      ## Let's talk


      I'd love to here from you and have some chat about anything and
      everything. How do you take your coffee?
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: GC CODES
  description: My personal blog where I share as I learn!
  value: /images/New Tab - Google Chrome 05-08-2021 12_50_35 (2).png
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: GC CODES
      keyName: property
    - name: 'og:description'
      value: My personal blog where I share as I learn!
      keyName: property
    - name: 'og:image'
      value: /images/New Tab - Google Chrome 05-08-2021 12_50_35 (2).png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: GC CODES
    - name: 'twitter:description'
      value: My personal blog where I share as I learn!
    - name: 'twitter:image'
      value: /images/New Tab - Google Chrome 05-08-2021 12_50_35 (2).png
      relativeUrl: true
layout: advanced
---
