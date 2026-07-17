# Day 15 – AI Content Generator Workflow using Google Sheets and n8n

## What I Learned

Today, I built an **AI Content Generator** workflow using **n8n** and **Google Sheets**. The goal was to automate social media content creation. Instead of writing captions manually, the AI generates content automatically whenever a new topic is added to a Google Sheet.

## Tools Used

* n8n
* Google Sheets
* Google Sheets Trigger
* AI Agent (Gemini/OpenAI)
* Google Sheets Update Row
* Structured Output

## Workflow Steps

1. Created a Google Sheet with columns:

   * Topic
   * Platform
   * Audience
   * Tone
   * Caption
   * Hashtags
   * Image Prompt

2. Added a **Google Sheets Trigger** node to start the workflow whenever a new row is added.

3. Connected an **AI Agent** and provided a prompt to generate:

   * Title
   * Caption
   * Hashtags
   * Image Prompt

4. Configured a **Structured Output** schema so the AI returned data in a consistent JSON format.

5. Used a **Google Sheets Update Row** node to write the generated content back into the same row automatically.

## What I Learned Today

* How to automate content generation with AI.
* How Google Sheets can trigger workflows in n8n.
* How Structured Output ensures AI responses follow a fixed format.
* How to update existing rows in Google Sheets automatically.
* How automation can save time for social media teams and content creators.

## Challenges Faced

* Understanding the Structured Output schema.
* Mapping AI-generated fields correctly to Google Sheets columns.
* Configuring the Update Row node to update the correct row.

## Outcome

By the end of the session, I successfully created an AI-powered workflow that generates social media content automatically and stores it in Google Sheets. This demonstrated how AI and automation can simplify repetitive content creation tasks.

## Images
(AI Content Generator)[https://github.com/navvdehar07/AI-AUTOMATION-AGENTIC-AI/blob/main/images/AI%20Content%20Generator.png]
