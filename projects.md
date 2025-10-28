---
layout: default
title: Projects
---
{% include header.md %}

# 🚀 Featured Projects

Explore some of my most innovative and technical work — covering AI, data pipelines, dashboards, and real-time systems.

---

## 👥 GhostWriter Teams
<img src="assets/GW-content calender.png" width="500" alt="GhostWriter" />

**Ghostwriter Teams** is your local AI-powered creative department — built to help marketers, creators, and startups brainstorm, write, plan, and critique content like a full-scale agency.

Run locally with open-source models like LLaMA 2 or Mistral (via Ollama), it features five specialized agents working together to produce end-to-end campaign strategies, content calendars, rewrites, and branding insights — all without needing any paid API keys.

---
Ghostwriter Teams simulates a multi-agent marketing team where each AI agent specializes in a unique creative function:

- **Zara** – Creative Strategist  
- **Max** – Content Architect  
- **Mira** – Research Analyst  
- **Eva** – Critic & Challenger  
- **Leo** – Brand Guardian  

You can brainstorm campaign ideas, generate structured content calendars, ask for rewrites, compare campaigns, and export your results — all through an intuitive Streamlit UI.

---

## ✨ Features

- **AI Agents as Roles** (Creative, Writer, Analyst, Critic, Brand Voice)
- **Full Content Calendar Generation** (Markdown tables with copy, dates, platforms)
- **Campaign Brainstorming + Rewrite Assistant**
- **Multilingual Output** (English, French, Hindi, Telugu, Japanese, and more)
- **Local LLM Runtime** with Ollama (LLaMA 2, Mistral, Gemma, etc.)
- **No API Keys Required**
- **Export Campaigns** as PDF, CSV, Markdown
- **Timeline Visualizations** with Altair & Plotly
- **Campaign Comparison & Dashboard View**

---

## 🚀 Example Use Case

> _"I want to launch an AI journaling app for moms. Help me plan 4 weeks of content on Twitter and LinkedIn."_

Ghostwriter responds with:
- A full **platform-specific calendar** of daily posts
- **Emotional hooks** and **CTA optimizations**
- **Eva’s critique** and **rewrite suggestions**
- **Mira’s insights** on trends, audience behavior, and timing
- **Leo’s brand voice check** to ensure tone alignment

Then, you export it all in Markdown, PDF, or CSV

**Tech Stack:** Streamlit · LangChain · Ollama · Local LLMs



---

## ⚡  [GetGetLeads – AI Lead-to-booking & Digital Marketing Agent](https://www.getgetleads.com/login)

<img src="GGL- Login page.png" alt="GetGetLeads Login" width="250" />
<img src="GGL- Demo page.png" alt="GetGetLeads Dashboard" width="350" />
<td width="60%">
GetGetLeads is a comprehensive, all-in-one platform designed specifically for small businesses in the salon, med spa, and real estate industries. It combines lead generation, CRM, email automation, social media automation, calendar management, and AI-powered content generation to help small businesses scale efficiently.

**Features:**
- Smart Lead Management
- AI-Powered Email Automation
- Calendar Integration
- Google Calendar two-way sync
- AI Content Generation
- Reviews & Referrals Automation
- Analytics Dashboard
- Niche-Specific Support
- Multi-platform posting and social automation

---

## ⚡ Key Features

- **Lead Generation** – Capture and score leads using AI-driven forms
- **Analytics Dashboard** – Visual insights into traffic, conversion, and ROI
- **SEO + Keyword Tracking** – Monitor rankings and optimize content
- **Budget Management** – Track ad spend, campaign costs, and performance
- **Campaign Automation** – Schedule and automate posts, emails, and outreach
- **Customer CRM** – Manage contacts, notes, and communication history
- **Social Media Automation** - upload social media content post, including tags based on users, interest, and schedule times

---

**Stack:** React · Supabase · Tailwind · OpenAI

---

## ✈️ GetGetPlaces – AI Travel Planning Agent
<img src="assets/Homepage-GGP.png" width="500" alt="GetGetPlaces" />

An intelligent NLP-powered travel planning platform with real-time weather, pricing, and smart routing.
Engineered a full-stack AI/ML solution for real-time personalized itinerary generation, synthesizing multi-source APIs (weather, hotel, transport) using time-series analysis, Location and optimization models, demonstrating scalable predictive analytics deployment

---

**Key Features:**
- Natural language trip planning: “Plan 5-day Miami trip with $1500”
- ARIMA price forecasting (flights, hotels)
- Route optimization + travel time estimates
- Smart daily itineraries with weather forecasts
- PostgreSQL backend for trip data

---

**Example Use:**
> “Plan a 7-day Orlando trip under $2500 focusing on theme parks and food” → Output: Day-wise schedule, attractions, maps, travel tips
---

**Stack:** PostgreSQL · ARIMA · OpenWeatherMap · LangChain

---

## 🎬 [Movie Recommendation System](https://mrs-sg-bfc2e6fa78db.herokuapp.com/)
<img src="assets/MRS Sample.png" width="500" alt="Movie Recommendation Engine" />

Built a content-based movie recommendation system using Python, Scikit-Learn, TensorFlow, NLTK, Pandas, and NumPy, applying NLP and similarity matching algorithms to analyze structured/unstructured data and generate personalized predictions.

---

**Features:**
- Content-based filtering on movie descriptions
- Enter a movie → Get top 5 similar films instantly
- Web app interface with Heroku deployment
  
---

**Example Use:**
> Input: “The Matrix” → Output: Sci-fi action recommendations like “Equilibrium”, “Inception”, etc.

---

**Stack:** Flask · NLTK · Pandas · Scikit-learn · TF-IDF Vectorizer

---

## 🐍 Snake Game
<img src="assets/PythonSnakeGame.gif" width="500" alt="Snake Game" />

A classic Snake game made using Python’s Tkinter GUI toolkit.

---

**Highlights:**
- Real-time movement and key-driven controls
- Score tracking and collision detection
- Minimalistic interface

---

**Example Use:**
> Launch the app → Arrow keys to control → Eat food to grow → Avoid crashing into walls

---

## 🏓 Pong Game AI – NEAT
<img src="assets/PythonPongGame-AI.gif" width="500" alt="Pong Game AI" />

Trains an AI to play Pong using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm.

---

**Features:**
- Evolution of neural networks via reinforcement
- AI adapts its paddle response to opponent's movement
- Visualization of evolving agent skill

---

**Example Use:**
> Launch → Watch AI learn after several generations → Compete against the bot

---

**Stack:** Python · NEAT-Python

---

## 📈 Real-Time Stock Market Analysis System 

Designed a live stock market trend prediction pipeline using AWS services (EC2, S3, Glue, Athena) and Kafka, building real-time data streaming architectures to deliver predictive investment insights.

---

**Features:**
- Live data ingestion via Kafka
- Transformation with AWS Glue and Spark
- Query using Athena and visualize in dashboards
- Use case: financial alerting, intraday trend monitoring

---

**Example Use:**
> Track tickers like AAPL, TSLA → Receive moving averages, trend shifts → Query on demand via Athena

---

**Stack:** AWS EC2 · Glue · Kafka · Athena · S3

---


🏠 [Back to Home](index.md) | 📄 [Experience](experience.md) | 📫 [Contact](contact.md)

