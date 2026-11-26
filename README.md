# HypeSmart AI — Creator, Budget & Smart-Choice Copilot

An AI-powered web application built for college students and young adults to generate high-retention short-form content hooks, audit recurring subscriptions for student discounts, and make objective weighted decisions—powered by an integrated, context-aware Gemini AI chatbot.

## 1. Problem Statement & Target Audience
- **Problem:** College students and young creators frequently struggle with three everyday bottlenecks: writer's block when scripting short-form content, silent monthly money leaks from forgotten subscriptions, and decision paralysis over tech purchases or career choices.
- **Solution:** HypeSmart AI unifies a **Viral Hook & Script Lab**, a **Student Subscription & Deal Tracker**, and a **Weighted Decision Matrix** into one responsive dashboard backed by a real-time Gemini AI copilot.
- **Target Audience:** College students, student creators, and young adults.

## 2. Features Implemented
- **Viral Hook & Script Lab:** Generates three tone-matched opening hooks, a 30-second beat-by-beat script, thumbnail cover text, and niche hashtags with one-click export to the AI Copilot for critique.
- **SubTracker & Student DealFinder:** Calculates monthly and annual subscription burn rates, flags rarely used services, and applies Student ID discount estimates.
- **Weighted Smart Decision Matrix:** Compares two competing choices across customizable criteria weights (1–10) with live percentage progress bars and AI devil's-advocate analysis.
- **Live Context-Aware AI Chatbot:** Communicates with the Gemini API using dynamic system instructions tailored to the active module, complete with input validation and error handling.

## 3. Technologies & AI Tools Used (3+ Tools)
- **Frontend & Hosting:** HTML5, Tailwind CSS, Vanilla JavaScript, Vercel Serverless Functions
- **Google Gemini:** Designed the 5-part architecture prompt, crafted domain-specific system instructions, and powers the live chatbot API.
- **ChatGPT / Claude:** Refined the weighted decision-matrix scoring logic, student discount heuristics, and prompt iterations.
- **Cursor / GitHub Copilot:** Assisted with responsive layout refactoring, DOM state synchronization, and API error-handling blocks.

## 4. Screenshots
*(Upload screenshots of your dashboard tabs and live chatbot responses to a `/screenshots` folder and link them below)*
- `![Hook Lab](./screenshots/hook-lab.png)`
- `![SubTracker](./screenshots/sub-tracker.png)`
- `![Decision Matrix & Chatbot](./screenshots/decision-copilot.png)`

## 5. Prompt Engineering Documentation
Full records of our 5-part initial prompt, iterative modifications, and before/after output comparisons are documented in [`PROMPTS.md`](./PROMPTS.md).

## 6. How to Run Locally & Deploy
1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/hypesmart-ai-copilot.git
   cd hypesmart-ai-copilot
