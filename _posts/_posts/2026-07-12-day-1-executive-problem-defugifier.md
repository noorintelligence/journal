---
layout: default
title: "Day 1: Executive Problem De-Fugifier"
date: 2026-07-12
categories: [ai-apps, client-side]
tags: [gemini-api, javascript, github-pages]
---

Today I launched the first project in my 14-day build challenge: **Executive Problem De-Fugifier**.

### 🛠️ What I Built
A browser-native tool that takes raw, ambiguous business problems, parses underlying business assumptions, infers a diagnostic KPI triad (Volume, Value, Retention), and outputs a structured **C-R-E-A-T-E** meta-prompt.

### 💡 Key Technical Takeaways
- **Zero-Backend Architecture:** Runs 100% client-side using standard JavaScript (`fetch` API) and Tailwind CSS.
- **Local Key Storage:** Keeps user API keys secure by managing them exclusively in the browser's `localStorage`.
- **Model Fallback:** Configured REST calls for both Google Gemini and OpenAI endpoints.

### 🔗 Deliverables
- **Live Application:** [Executive Problem De-Fugifier](https://noorintelligence.github.io/executive-problem-defugifier/)
- **GitHub Repository:** [noorintelligence/executive-problem-defugifier](https://github.com/noorintelligence/executive-problem-defugifier)

---
*Build. Test. Learn. Improve. Share.*
