---
name: Today I learned
about: Today I learned
body:
  - type: input
    id: title
    attributes:
      description: The til title
    validations:
      required: true
  - type: input
    id: path
    attributes:
      description: The path which be used to create a new file
    validations:
      required: true
  - type: textarea
    id: body
    attributes:
      description: Insert your til content
---

\-\-\-
title:
path: The path which be used to create new file
\-\-\-
