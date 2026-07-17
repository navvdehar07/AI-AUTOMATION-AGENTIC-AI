# Day 16 - AI Content Repurposer Workflow using n8n

## Overview

Today, I built an **AI Content Repurposer Workflow** using **n8n**. The workflow automatically generates content for multiple social media platforms from a single topic entered in Google Sheets. I also learned how to generate an AI image, upload it to Google Drive, and update the Google Sheet with all the generated content.

---

## What I Learned

- Learned how to trigger a workflow automatically using Google Sheets.
- Used an AI Agent to generate content for different social media platforms.
- Learned how to use Structured JSON Output.
- Understood how AI image generation works using an Image Prompt.
- Learned how to upload generated images to Google Drive.
- Learned how to update Google Sheets automatically with generated data.

---

## Tools Used

- n8n
- Google Sheets
- Google Gemini AI
- Structured Output Parser
- HTTP Request Node
- Google Drive

---

## Workflow Steps

1. Created a Google Sheet with Topic, Audience, and Tone columns.
2. Used Google Sheets Trigger to start the workflow automatically.
3. Generated:
   - Instagram Caption
   - LinkedIn Post
   - Facebook Post
   - Twitter/X Thread
   - Blog Introduction
   - YouTube Title
   - YouTube Description
   - Email Newsletter
   - Image Prompt
4. Received the output in Structured JSON format.
5. Generated an AI image using the Image Prompt.
6. Uploaded the generated image to Google Drive.
7. Updated the Google Sheet with all generated content and the image link.
8. Used a Status column to track the workflow progress.

---

## Challenges Faced

- Faced issues while mapping fields in the Google Sheets Update node.
- Learned the correct way to map AI Agent outputs.
- Understood how to update the correct row in Google Sheets.

---

## Key Takeaways

- One topic can be converted into content for multiple platforms automatically.
- Structured JSON makes AI workflows more organized.
- Google Sheets and Google Drive can be integrated easily with n8n.
- AI automation saves time and improves productivity.

---

## Image
[AI Content Repurposer](https://github.com/navvdehar07/AI-AUTOMATION-AGENTIC-AI/blob/main/images/AI%20Content%20Repurposer.png)
