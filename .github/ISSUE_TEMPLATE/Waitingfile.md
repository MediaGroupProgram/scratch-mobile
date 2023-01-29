
name: Waiting Line ⌛
description: If alls places are used.
title: "Waiting Line ⌛ "
labels: [""]
assignees:
  - octocat
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you to send you status of the line?
      placeholder: ex. email@example.com
    validations:
      required: true
    - type: input
    id: password
    attributes:
      label: Password
      description: Please enter your password.
      placeholder: ex. mediageoupprogramtech123ABCabc
    validations:
      required: false
  - type: checkboxes
    id: getcheck
    attributes:
      label: I accept that e-mail and password is sended to @AmixemHello for the bot.

      description: By submitting this issue, you agree to exchange your e-mail and password to AmixemHello.
      options:
        - label:  I agree to exchange my e-mail and password to AmixemHello for the bot.
          required: true
