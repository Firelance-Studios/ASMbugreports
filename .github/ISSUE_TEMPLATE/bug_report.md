name: Bug Report
description: Submit a bug
title: "Bug: <Title>"
labels: ["Bug"]
body:
- type: textarea
  attributes:
    label: Describe the bug
    description: A clear description of what the bug is. Pictures/videos are great!
    placeholder: |
      When I do X then Y happens.
  validations:
    required: true
- type: textarea
  attributes:
    label: Issue Map
    description: A map that the issue occurs on. 
    placeholder: |
      What map does this bug happen on?
  validations:
    required: true
- type: textarea
  attributes:
    label: To Reproduce
    description: Steps to reproduce the behavior
    placeholder: |
      1. Open map [...]
      2. Do [...]
      3. Error occurs
  validations:
    required: true
