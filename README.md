<a href="https://wa.me/525565659395">
  <img 
  alt="2026 World Cup Mexico City AI chatbot."
  src="https://github.com/user-attachments/assets/df9a58cd-fc69-4b01-ab51-f9f20ccba0d6"
/>
  <h1 align="center">Xoli</h1>
</a>

<p align="center">
  An Open-Source AI Chatbot for the 2026 FIFA World Cup in Mexico City.
</p>

<p align="center">
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#xoli-overview"><strong>Xoli Overview</strong></a> ·
  <a href="#ai-experience"><strong>AI Experience</strong></a> ·
  <a href="#deploy-your-own"><strong>Deploy Your Own</strong></a> ·
  <a href="#running-locally"><strong>Running locally</strong></a>
</p>
<br/>

## Features

- [Next.js](https://nextjs.org) App Router
  - Advanced routing for seamless navigation and performance
  - React Server Components (RSCs) and Server Actions for fast, server-side rendering
  - Optimized for mobile users traveling around Mexico City during the tournament

- [AI SDK](https://sdk.vercel.ai/docs)
  - Unified API for generating text, structured objects, and tool calls with LLMs
  - Streaming AI chat experience for fans and travelers
  - Supports Google Gemini, OpenAI, Anthropic, Cohere, and more

- World Cup Fan Experience
  - Match schedules, stadium guides, and transportation tips
  - Local recommendations for restaurants, nightlife, and fan zones
  - Personalized travel itineraries for visitors in Mexico City
  - Multi-language support for international fans

- [shadcn/ui](https://ui.shadcn.com)
  - Styling with [Tailwind CSS](https://tailwindcss.com)
  - Accessible component primitives powered by [Radix UI](https://radix-ui.com)

- Data Persistence
  - [Vercel Postgres powered by Neon](https://vercel.com/storage/postgres) for chat history and saved itineraries
  - [Vercel Blob](https://vercel.com/storage/blob) for media and object storage

- [NextAuth.js](https://github.com/nextauthjs/next-auth)
  - Simple and secure authentication for returning users

## Xoli Overview

Xoli acts as a digital concierge for tourists and locals exploring Mexico City during the 2026 FIFA World Cup.

| Feature | Description |
|---|---|
| **Service** | 24/7 WhatsApp chatbot for tourists |
| **Languages** | English and Spanish |
| **Functionality** | Provides info on culture, tourism, mobility, and FIFA World Cup |
| **Key Users** | Tourists and locals |
| **Accessibility** | Available on WhatsApp via +52 55 6565 9395 |
| **Post-World Cup** | Continues to serve visitors and residents |

## AI Experience

Xoli helps fans navigate the 2026 FIFA World Cup in Mexico City with real-time AI assistance.

Example prompts:

- “How do I get to Estadio Azteca from Condesa?”
- “Where can I watch tonight’s Brazil match?”
- “Give me a 2-day football itinerary in Mexico City.”
- “What local food should I try near the stadium?”
- “Which neighborhoods are best for World Cup visitors?”

## Deploy Your Own

You can deploy your own version of Xoli to Vercel with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

## Running locally

You will need to use the environment variables defined in `.env.example` to run Xoli locally.

It’s recommended you use [Vercel Environment Variables](https://vercel.com/docs/projects/environment-variables), though a local `.env` file also works.

> Note: Do not commit your `.env` file or it may expose API keys and authentication secrets.

1. Install Vercel CLI:

```bash
npm i -g vercel
