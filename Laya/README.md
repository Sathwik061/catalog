---
template: "laya template.json"
category: Connectors
tags:
  - laya
  - decision
  - ai
  - classification
  - approval
---

# Laya Decision

Send assessment text to a Laya decision model and receive a structured decision containing probabilities, confidence and other response details. Map the decision into approved, rejected or review outcomes for automated BPMN process execution.

## Usage

Apply this template to a **Service Task** in your BPMN diagram and configure the Laya decision endpoint, authentication headers and assessment text in the properties panel.

Configure the decision field, approve and reject choices, and define how other outcomes (such as review) should be handled. Map the resulting decision values to your BPMN gateway conditions.

The connector sends the assessment to the Laya decision API and stores the response in the configured result variable. Configure the result expression to map the response into process variables.
