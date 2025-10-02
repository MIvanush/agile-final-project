---
name: Issue
about: For Assessment
title: ''
labels: ''
assignees: ''

---

name: User Story
description: Create a user story for a product feature.
title: "[Story] <Feature Description>"
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        ## User Story
  - type: input
    id: user-story
    attributes:
      label: As a...
      description: Who is the user?
    validations:
      required: true
  - type: input
    id: need
    attributes:
      label: I need...
      description: What is the need?
    validations:
      required: true
  - type: input
    id: so-that
    attributes:
      label: So that...
      description: Why is this important?
    validations:
      required: true
  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance Criteria
      description: Use Given/When/Then format
    validations:
      required: false
