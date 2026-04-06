# AI Content Creator Agent using n8n

## Project Overview

This project implements a no-code AI-powered content creation workflow using n8n. The workflow automatically identifies topics from Google Sheets, performs research using Tavily Search API, generates platform-specific content using AI, and updates the results back into Google Sheets.

## Workflow Steps

1. Read topic from Google Sheets
2. Retrieve research data using Tavily Search API
3. Generate LinkedIn post using AI
4. Generate X (Twitter) post using AI
5. Generate Blog Summary
6. Update Google Sheet with generated content and mark status as Completed

## APIs Used

* Tavily Search API
* Google Gemini API
* Google Sheets API

(Note: API keys are not included for security reasons.)

## Sample Input

Topic: Future of AI in Healthcare

## Sample Output

LinkedIn Post:
AI is rapidly transforming healthcare by enabling faster diagnosis, improving treatment planning, and accelerating medical research...

X Post:
AI is revolutionizing healthcare! From smarter diagnostics to personalized treatments, the future of medicine is intelligent. #AI #Healthcare

Blog Summary:
Artificial Intelligence is transforming healthcare through advanced data analysis, predictive modeling, and automation. Hospitals and researchers are using AI to detect diseases earlier, improve patient outcomes, and optimize healthcare systems.

## Prompt Design

LinkedIn Prompt:
Professional tone, 120–150 words, engaging and insightful.

X Prompt:
Short tweet under 280 characters with relevant hashtags.

Blog Prompt:
150–200 word informative summary explaining the topic clearly.
