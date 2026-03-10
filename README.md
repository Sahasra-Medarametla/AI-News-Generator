**AI News Summarizer using n8n**

**Introduction**

This project builds an AI News Summarizer using n8n.
The system automatically collects the latest AI and technology news, summarizes it using Gemini AI, and sends a daily newsletter email.

Instead of visiting many websites every morning, you receive a short summary of important news directly in your inbox.

**Problem**

Staying updated with tech news usually requires:

-Visiting many websites

-Reading multiple articles

-Filtering useful information

⏱ Time taken: 30–45 minutes every day

**Solution**

This workflow automates the process:

-Fetches news from RSS feeds

-Searches the internet for AI events

-Uses Gemini AI to summarize content

-Sends a daily email newsletter

⏱ Time required: Less than 2 minutes

**Tools Used**

n8n – Workflow automation platform

Google Gemini AI – Content summarization

RSS Feeds – Fetch latest news

SERP API – Search live events from the internet

Gmail – Send email newsletter

**How RSS Feeds Work**

RSS feeds allow websites to automatically send updates when new content is published.

Example RSS feeds:

https://aibusiness.com/rss.xml

https://techcrunch.com/category/artificial-intelligence/feed/

https://www.reddit.com/r/technology/.rss

The workflow collects news from these feeds automatically.

**Workflow Steps**

-Schedule Trigger
Runs the workflow automatically every day.

-Fetch News from RSS Feeds
Collects AI and technology news from multiple websites.

-Fetch Live Events using SERP API
Searches the internet for the latest AI events and updates.

-Merge and Aggregate Data
Combines all news and event information.

-AI Summarization
Gemini AI creates a short and clear summary.

-Send Email Newsletter
The summarized news is sent to your email.

**Workflow Architecture**

Schedule Trigger

↓

Fetch RSS News

↓

Fetch Live Events (SERP API)

↓

Merge Data

↓

AI Summarization (Gemini)

↓

Send Email via Gmail

**Benefits**

-Automatic news collection

-AI-powered summarization

-Daily email updates

-Saves 30+ minutes every day

**Future Improvements**

-Add more RSS news sources

-Include AI-generated images

-Send notifications via Slack or Telegram

-Add topic-based filtering
