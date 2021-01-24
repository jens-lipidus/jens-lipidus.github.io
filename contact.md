---
stackbit_url_path: /contact
no_index: false
layout: landing
sections:
  - type: section_contact
    form_fields:
      - type: form_field
        is_required: true
        label: Name
        name: name
        input_type: text
      - type: form_field
        is_required: true
        label: Email
        name: email
        input_type: email
      - type: form_field
        is_required: false
        options:
          - Error on the site
          - Sponsorship
          - Other
        label: Subject
        name: subject
        default_value: Please select
        input_type: select
      - type: form_field
        is_required: false
        label: Message
        name: message
        input_type: textarea
      - type: form_field
        is_required: true
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        name: consent
        input_type: checkbox
    submit_label: Send Message
    hide_labels: false
    content: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
      quis lorem malesuada luctus. Cras lacinia, eros at dapibus molestie, risus
      tortor pretium ligula.
    background: gray
    form_id: contactForm
    title: Contact
    section_id: contact
title: Contact
---
