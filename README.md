# ai-news-digest-n8n
An automated news aggregation and AI summarization workflow built with n8n and Gemini that delivers a clean daily news digest via email.
# 📰 AI News Digest Automation (n8n)

An automated workflow built with n8n and Gemini that collects news from multiple RSS sources (HINDUSTAN TIMES) , summarizes each article using AI, and sends a single daily email digest.

## What It Does
- Aggregates news from multiple RSS feeds
- Limits and processes articles efficiently
- Generates short AI-based summaries
- Combines all summaries into one email
- Sends the digest automatically via email

## Workflow
RSS Feeds → Merge → Limit → Split Out → AI Model → Aggregate → Email

## Tech Stack
- n8n
- Gemini (GPT models)
- RSS Feeds
- Gmail 

## Setup
1. Import the workflow JSON into n8n  
2. Add OpenAI and Email credentials  
3. Set RSS sources and recipient email  
4. (Optional) Add a Cron trigger

## Author
Kaustubh Kishor Nikam 



