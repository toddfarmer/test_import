name: Bug report
about: Create a report to help us improve
title: ''
labels: 'Type: bug'
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!!!
  - type: checkboxes
    id: new-bug
    attributes:
      label: Is there an existing issue for this?
      description: Please search to see if an issue already exists for the bug you encountered.
      options:
      - label: I have searched the existing issues
        required: true
  - type: textarea
    id: bug-description
    attributes:
      label: Description of the bug
      description: Tell us what bug you encountered and what should have happened
    validations:
      required: true
  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: Steps To Reproduce
      description: Steps to reproduce the behavior.
      placeholder: Please write the steps in a list form
    validations:
      required: true
  - type: dropdown
    id: versions
    attributes:
      label: Which version of the app are you using?
      description: If this issue is occurring on more than 1 version of the app, select the appropriate versions.
      multiple: true
      options:
       - 1.0.0
       - 1.1.0
       - 1.2.0
       - 2.0.0
       - 2.1.0
    validations:
      required: true
**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Desktop (please complete the following information):**
 - OS: [e.g. iOS]
 - Browser [e.g. chrome, safari]
 - Version [e.g. 22]

**Smartphone (please complete the following information):**
 - Device: [e.g. iPhone6]
 - OS: [e.g. iOS8.1]
 - Browser [e.g. stock browser, safari]
 - Version [e.g. 22]

**Additional context**
Add any other context about the problem here.
