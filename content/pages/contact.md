---
title: Contact
sections:
  - type: hero_section
    title: Contact Me
    subtitle: Fill out the form below and I will get in touch within 1 business day.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >+
      # Let's talk


      I'd love to here from you and have some chat about anything and
      everything.


      How do you take your coffee?


      ![](/images/great-tiger.png)

    content_align: left
    form_position: left
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
  title: Contact
  description: This is the contact page.  I will reach you as soon as possible!
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page. I will reach you as soon as possible!
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page. I will reach you as soon as possible!
    - name: 'og:image'
      value: >-
        /images/gc-codes - Stackbit App - Google Chrome 06-08-2021 09_56_48
        (2).png
      keyName: property
      relativeUrl: true
layout: advanced
---
