name: 🐞 Bug Report
description: File a bug report
title: "[BUG]: "
labels: [bug]
body:
  - type: textarea
    attributes:
      label: What happened?
      description: A clear and concise description of what the bug is.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Steps to reproduce
      description: Describe steps to reproduce this issue.
      placeholder: |
        1. Go to...
        2. Click on...
        3. Scroll down...
        4. See error
    validations:
      required: true

  - type: input
    attributes:
      label: What should have happened?
      description: Describe the expected behavior.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Screenshots or logs
      description: If applicable, add screenshots or error logs.

  - type: input
    attributes:
      label: Environment (device, OS, browser, etc.)
