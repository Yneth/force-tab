name: Feature request
description: File a feature request
title: "[FEATURE]: "
labels: ["feature"]
assignees:
  - Yneth
body:
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: feature-description
    attributes:
      label: As a user I would like to
      description: 
      placeholder: have a possibility to do XXX.
      value: ""
    validations:
      required: true
