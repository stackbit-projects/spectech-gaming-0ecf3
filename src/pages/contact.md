---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: To get in touch please fill the form below.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Full Name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: number
        name: Con
        label: lorem-ipsum
        default_value: lorem-ipsum
        options: []
        is_required: false
        type: form_field
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - New PC Build
          - Upgrade to existing Build
          - Cleaning or Repairs
          - Error on Site / Problem contacting
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
template: advanced
---
