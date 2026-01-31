🚀 AI Content Repurposing System

An AI-powered content automation system that converts a single keyword into a full content ecosystem, including a blog post and platform-specific social media content. Built for scalability, brand consistency, and real-world production use.

**📌 Project Overview**

This project automates the entire content repurposing workflow using n8n, OpenAI, Airtable, and a Vercel-hosted frontend.

Instead of manually rewriting content for different platforms, users enter one keyword through a web interface. The system then automatically generates a long-form blog and optimized social media posts for multiple platforms, stores them in Airtable, and returns the results to the frontend in real time.

The primary goal is to eliminate manual content repurposing while maintaining brand awareness and platform-specific writing rules.

**Features**

Single keyword input through a web-based UI

Automated generation of:

SEO-optimized blog post

X (Twitter) thread

LinkedIn post

Facebook post

Instagram caption

Brand-aware content using a dynamic company profile

Real-time content rendering on the frontend

Centralized content storage in Airtable

Stable and scalable workflow using normalized data references

**🏗️ System Architecture**

**High-level flow:**

>User enters a keyword on the frontend

>Frontend sends the keyword to an n8n webhook

>n8n normalizes input and fetches company context from Airtable

>OpenAI generates blog and social media content

>All outputs are saved to Airtable

>Final structured data is returned to the frontend

>Frontend displays content in copy-ready cards

💻 Tech Stack

**Automation** : n8n

**AI**: OpenAI

**Database** : Airtable

**Frontend**:HTML, CSS, JavaScript

**Hosting**:Vercel

**🧩 n8n Workflow Highlights**

Webhook Node: Entry point for frontend requests

Set Node: Normalizes keyword input for stable references

Airtable Node: Fetches dynamic company profile data

AI Blog Generator: Creates long-form content

Platform-Specific AI Nodes: Generate tailored posts for each platform

Merge Node: Combines all outputs into a single object

Airtable Save Node: Stores final content permanently

Respond to Webhook: Sends structured response back to frontend

**🧪 Data Normalization Strategy**

To avoid fragile references like webhook item paths, all downstream nodes rely on:

**$json.keyword**


This approach improves:

Workflow stability

Debugging simplicity

Long-term scalability

**🔐 Security**

Airtable accessed via Personal Access Tokens

OpenAI API keys are securely stored in n8n credentials

**⚙️ Customization & Extensibility**

Prompt Control

Modify AI prompts to change:

Tone (formal, conversational, technical)

Content type (educational, how-to, thought leadership)

Structure (headings, paragraph length, CTAs)

Company Profile

Update brand details directly in Airtable:

Company name

Services

Target audience

Tone and positioning

Geographic focus

**All AI outputs automatically adapt to changes without modifying the workflow.**

**Future Extensions**

>Social media auto-publishing

>CMS integration (WordPress, Webflow)

>Approval and scheduling workflows

>Analytics and usage tracking

>Multi-language support

**📈 Use Cases**

SEO teams

Content marketing agencies

Consultants

Founders building content engines

**✅ Final Outcome**

This project demonstrates a production-ready AI automation pipeline that transforms a single keyword into a complete, multi-platform content set with minimal human involvement.
