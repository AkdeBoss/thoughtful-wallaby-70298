---
title: Contact
sections:
  - section_id: contact_us
    type: section_contact
    background: gray
    title: Have a query?
    content: >
      We offer a dedicated fleet at competitive pricing for your long-term
      business needs. transparent process and digital integration make us one of
      the strongest contenders in your logistical needs, we work with you to
      ensure we deliver the best of the results by constantly learning and
      upgrading our systems to ensure scalability.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Long term contract
          - Short term contract
          - On-demand contract
          - Other
          - lorem-ipsum
        is_required: true
      - input_type: textarea
        name: message
        label: Message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    subtitle: 'Write to us, we''ll get you the best deal.'
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: landing
---
