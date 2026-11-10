# SEGUN — AI Assistant

SEGUN (Simi's Enhanced Generative Utility Network) is a conversational AI assistant with a custom persona, built with Python, FastAPI and LangChain.

## Stack
Python, FastAPI, LangChain (ChatAnthropic), Anthropic Claude API, HTML/CSS/JS frontend

## Features
- Custom persona
- API key stored server-side in `.env`, never exposed to the browser
- FastAPI backend with LangChain handling the model calls

## Run it locally
1. Clone the repo
2. Create and activate a virtual environment
3. `pip install -r requirements.txt`
4. Copy `.env.example` to `.env` and add your Anthropic API key
5. Start the server with: [your run command]

## Status
Working locally. [Add what's still in progress.]

## Background
Ported from an earlier Node.js/Express version (Jarvis), which had no memory, tools, auth, or server-side key handling.
