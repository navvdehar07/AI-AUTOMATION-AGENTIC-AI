# Day 17 – AI Support Triage Agent Workflow

## Overview

Today, I built an **AI Support Triage Agent** workflow using **n8n**. The goal of this workflow is to automate the process of handling customer support messages. Instead of manually reading every message, the AI analyzes the request, classifies it, decides its urgency, and routes it to the appropriate branch.

## What I Learned

* How AI can classify customer support messages.
* How to create decision-based workflows using the **IF** node.
* The importance of **Human-in-the-Loop (HITL)** for sensitive or uncertain cases.
* How to draft automatic replies for routine support requests.
* How to add error handling to improve workflow reliability.

## Tools Used

* n8n
* Webhook Trigger
* AI Agent (Google Gemini/OpenAI)
* IF Node
* Respond to Webhook
* Email/Slack (Human Review)
* Error Handling (Retry on Fail)

## Workflow Steps

1. Created a **Webhook Trigger** to receive customer support messages.
2. Connected the webhook to an **AI Agent**.
3. Configured the AI Agent to:

   * Classify the message (Billing, Technical, or General)
   * Assign an urgency level (Low, Medium, High)
   * Decide whether the case is Routine, Sensitive, or Ambiguous
   * Generate a draft reply for routine requests
4. Added an **IF Node** to check the AI's classification.
5. Routed routine messages to the automatic reply branch.
6. Routed urgent, sensitive, or ambiguous messages to a human reviewer using email.
7. Enabled retry/error handling so AI failures would not silently stop the workflow.
8. Tested the workflow with both routine and urgent customer messages.

## Key Concepts

* AI-powered message classification
* Decision-based workflow automation
* Human-in-the-Loop (HITL)
* Automatic response generation
* Error handling and retries
* Customer support automation

## Outcome

By the end of today's session, I successfully created an AI-powered support workflow that can automatically respond to routine customer queries while safely escalating sensitive or uncertain cases to a human reviewer. This project helped me understand how AI and workflow automation can improve customer support efficiency while maintaining human oversight for important decisions.

## Image
[AI Support Triage Agent](https://github.com/navvdehar07/AI-AUTOMATION-AGENTIC-AI/blob/main/images/AI%20Support%20Triage%20Agent.png)
