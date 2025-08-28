name: "Feature request"
description: "Propose a user-facing change"
labels: ["feat"]
title: "feat(<scope>): <short summary>"
body:
  - type: input
    id: scope
    attributes:
      label: Scope
      placeholder: island | media | layout | window | animation | appkit | swiftui
  - type: textarea
    id: summary
    attributes:
      label: Summary
      description: What and why
  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance criteria
      description: Checklist of outcomes
      value: |
        - [ ] …
  - type: textarea
    id: design
    attributes:
      label: Notes / design links
