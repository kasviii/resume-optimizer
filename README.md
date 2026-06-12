# Resume Optimizer 📄

> *Powered by my sheer will to make anything that might get me hired*

A free, AI-powered resume optimization tool that scores your resume against a job description, identifies missing keywords, rewrites bullet points using the STAR method, and gives you actionable improvement tips — all in the browser, no sign-up required.

**[→ Try it live](https://kasviii.github.io/resume-optimizer/)**

---

## What it does

Paste your resume and a job description, hit **Analyze & Optimize**, and get back:

- **Match score out of 100** — how well your resume aligns with the job (ATS-style scoring)
- **Missing keywords** — terms from the job description that aren't in your resume
- **4 rewritten bullet points** — using the STAR method (Situation, Task, Action, Result), tailored to the role, with one-click copy
- **Improvement suggestions** — specific, actionable tips to strengthen your application

---

## Tech stack

- Pure HTML/CSS/JS — single file, zero dependencies, zero build step
- [Groq API](https://console.groq.com) (free tier) running `llama-3.3-70b-versatile` for fast inference
- GitHub Actions for CI/CD — injects the API key at deploy time so it never appears in source
- GitHub Pages for hosting


- Groq free tier has rate limits — if you share this widely and hit them, requests will fail temporarily
- The deployed page has the API key visible in page source (it's baked in at build time) — this is a known trade-off for a free static deployment. Set a spending cap on your Groq account as a safety net.
- Best results with detailed resumes and full job descriptions — the more context, the better the output

---

*Hope you get the job, and so do I lolll*
