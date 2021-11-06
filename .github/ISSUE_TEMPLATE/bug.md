name: Bug Report
description: File a bug report
title: "[Bug]: "
labels: ["bug"]
assignees:
  - Yneth
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
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
  - type: input
    id: version
    attributes:
      label: Version
      description: What version of our plugin are you running?
	  placeholder: 1.0.0
    validations:
      required: true
  - type: input
    id: browser
    attributes:
      label: Browser version
      description: What chrome browser version are you seeing the problem on?
	  placeholder: 95.0.4638.54 (Official Build) (x86_64)
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks. You can find logs in chrome://extension page
      render: shell
