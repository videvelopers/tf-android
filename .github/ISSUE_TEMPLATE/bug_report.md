---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

name: Bug Report
description: Report a bug or unexpected behavior in Tech-Freedom
title: "[Bug]: "
labels: ["bug"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        Thank you for helping improve **Tech-Freedom for Visually Impaired** 🙏  
        Please fill out the details below so we can investigate the issue quickly.

  - type: textarea
    id: issue_description
    attributes:
      label: 1. Issue Description
      description: Clearly describe the problem you are facing.
      placeholder: Tell us what happened...
    validations:
      required: true

  - type: input
    id: app_version
    attributes:
      label: 2. Tech-Freedom Version
      description: You can find this in Settings → About.
      placeholder: e.g., 1.2.0
    validations:
      required: true

  - type: textarea
    id: actual_behavior
    attributes:
      label: 3. Actual Behaviour
      description: What actually happened?
      placeholder: Describe what the app did...
    validations:
      required: true

  - type: textarea
    id: expected_behavior
    attributes:
      label: 4. Expected Behaviour
      description: What did you expect to happen?
      placeholder: Describe the expected result...
    validations:
      required: true

  - type: input
    id: android_version
    attributes:
      label: 5. Android Version
      description: Check in Settings → About Phone → Android Version.
      placeholder: e.g., Android 14
    validations:
      required: true

  - type: textarea
    id: device_info
    attributes:
      label: 6. Device Information
      description: Include device brand, model, and any other relevant details.
      placeholder: e.g., Samsung Galaxy S23, 8GB RAM
    validations:
      required: true
