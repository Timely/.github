name: Service Request
description: A request for action, support, help for any internal operational or functional issue not immediately related to the capabilities of Timely itself.
title: "[Service Request]: "
labels: ["Type: Service Request", "Product: Timely"]
assignees:
  - lisarost
body:
  - type: markdown
    attributes:
      value: |
        Is this something we're doing for a customer, or is it internal?
  - type: dropdown
    id: sr-type
    attributes:
      label: Type of service request
      description: Is this something we're doing for a customer or lead, or is it internal?
      options:
        - External (for a customer/lead)
        - Internal (for ourselves)
    validations:
      required: true
  - type: input
    id: workspace-id
    attributes:
      label: Workspace ID
      description: If external, please input the workspace ID.
      placeholder: ex. 4301504
    validations:
      required: false
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
  - type: dropdown
    id: browsers
    attributes:
      label: What browsers are you seeing the problem on?
      multiple: true
      options:
        - Firefox
        - Chrome
        - Safari
        - Microsoft Edge
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://example.com)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
