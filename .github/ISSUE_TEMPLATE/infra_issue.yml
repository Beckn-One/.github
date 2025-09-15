name: Infrastructure Issue Report
description: Quickly report an issue with our IaaS service
title: "[ISSUE]: "
labels: [needs-triage]

body:
  - type: dropdown
    id: service
    attributes:
      label: Affected Service
      description: Select the main service where you observed the issue
      options:
        - Registry
        - Catalog Discovery Service
        - Beckn ONIX
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Issue Description
      description: Provide a brief description of the issue
      placeholder: What went wrong?
    validations:
      required: true

  - type: textarea
    id: attachments
    attributes:
      label: Attachments
      description: Paste logs, screenshots, or error messages here
      placeholder: Drag and drop files, or paste relevant logs/screenshots.
      render: shell
