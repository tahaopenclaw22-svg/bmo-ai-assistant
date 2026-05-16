# BMO Client Intelligence Assistant

An AI-powered pre-meeting research tool for banking professionals. Enter a company name and receive a structured client intelligence brief in seconds, built from live web data.

![BMO Client Intelligence](https://img.shields.io/badge/Built%20with-Claude%20AI-blue)

## What It Does

A relationship manager types in a company name — say, "Shopify Inc" — and the assistant:

1. Searches the web in real time for current news, earnings, and market data
2. Synthesizes findings using Claude AI
3. Streams back a structured brief with these sections:
   - Company Snapshot
   - Recent Developments
   - Risk Flags
   - Opportunities
   - Banker Talking Points

## Tech Stack

- **Frontend** — HTML, CSS, vanilla JavaScript with streaming UI
- **Backend** — Node.js + Express
- **AI** — Anthropic Claude API with web search tool use
- **Key concepts** — Streaming responses, tool use / MCP, REST API, environment variable security

## Setup

1. Clone the repo