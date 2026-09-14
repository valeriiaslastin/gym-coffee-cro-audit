# Gym+Coffee — E-commerce CRO & Technical SEO Audit

A hands-on CRO, UX, and technical SEO audit of **Gym+Coffee** (`gympluscoffee.com`), a popular Irish athleisure and lifestyle brand. 

* **Author:** Valeriia Slastin
* **Role:** UX & Digital Growth Analyst
* **Date:** September 2026
* **Primary Deliverable:** Executive presentation deck (`GymCoffee_CRO_SEO_Audit_Valeriia_Slastin.pdf`)

---

## 🎯 About the Project
I wanted to look under the hood of a major e-commerce player in Ireland. This project dives straight into the Gym+Coffee website to spot where they're leaking conversions, where users get stuck, and what's hurting their visibility on Google. 

By combining UX heuristics, consumer psychology, and crawler data (Screaming Frog), I uncovered **three core conversion roadblocks** and **three major technical SEO risks** — plus a practical, phased plan to fix them.

---

## 🔍 Key Findings

### 1. UX & Conversion Rate Optimization (CRO)
* **Above-the-Fold Overload:** When visitors land on the homepage, they immediately hit product grids without any quick story about who the brand is or why they're great. It adds unnecessary friction for new traffic.
* **Missing Trust Signals:** Product pages and hero sections don't lean heavily enough on reviews, social proof, or UGC, making people hesitate right before buying.
* **Retention Levers Left Behind:** Email popups don't offer an instant first-purchase incentive, and the loyalty rewards are hidden away in the footer, missing easy wins for cart recovery and repeat sales.

### 2. Technical SEO Audit (Screaming Frog Crawl)
* **Crawl Scope:** Analyzed 467 site-wide URLs to check indexation health and performance.
* **Server Throttling (429 Errors):** A massive 74% of HTML pages threw `429 Too Many Requests` errors during the crawl. This points to aggressive server/CDN rate-limiting that could mess with Googlebot's ability to properly index the site.
* **Metadata Gaps:** Big commercial category paths (like `/collections/all` or `/leggings`) completely missed meta descriptions, leaving Google to guess snippets and dropping organic CTR.
* **Title Tag Issues:** Key pages went over the standard SERP character limit (~60 chars), cutting off important keywords in search results.

---

## 🗺️ Action Plan (Phased Approach)
Here is how I structured the recommendations for design and dev teams to tackle without burning out:
* **NOW (0–2 weeks):** Fix the server/CDN 429 rate-limiting, write the missing meta descriptions, and clean up long title tags to protect organic search traffic right away.
* **NEXT (2–6 weeks):** Redesign the hero section for better brand storytelling, add prominent review feeds, and set up clear incentives for signups and rewards.
* **ONGOING:** Keep an eye on crawl health, indexation, organic CTR, and run continuous CRO tests.

---

## 📁 Repository Contents
* `GymCoffee_CRO_SEO_Audit_Valeriia_Slastin.pdf` — The full 7-slide strategic audit presentation deck.

---
*Built as part of my portfolio showcasing practical skills in UX analytics, digital growth, and technical SEO.*
