# Revlytics - Customer Voice Command Center

A premium, interactive customer sentiment analysis dashboard designed for **E-commerce Brand Owners** who receive thousands of customer reviews monthly across fragmented online platforms.

This solution acts as a centralized **Command Center**, converting noisy customer reviews into structured operational actions, product iterations, and revenue opportunities.

---

## 💡 The Problem & The Solution

### **The Problem Statement**
> *"We are a software company and we want to build a solution for an E-commerce Brand Owner. They keep getting 1000s of reviews on multiple online platforms every single month."*

E-commerce Brand Owners dealing with high review volumes suffer from **Information Overload**, **Data Fragmentation**, and **Analysis Paralysis**. Reading reviews manually across Shopify, Amazon, Flipkart, and Google is impossible to scale, leading to delayed responses, missed customer complaints, and missed market opportunities.

### **The Solution (Revlytics)**
Revlytics aggregates feedback databases, analyzes sentiment patterns, and highlights immediate risk areas. 
* **Centralization**: All platforms (Amazon, Flipkart, Shopify, Google) are brought into a single workspace.
* **Volume Synthesis**: Thousands of reviews are condensed into a high-level **Brand Health Score**, **AI Weekly Brief**, and **Love/Friction driver charts**.
* **Actionability**: Raw feedback is translated into step-by-step business actions (e.g., SLA checklist, Product SKU calculations).

---

## 🚀 Key Features

### 1. Unified Dashboard Overview
* **Brand Health Score**: A weighted sentiment score out of 100 with week-over-week progress trackers.
* **Total Reviews Counter**: Keeps track of review volumes across all connected marketplaces.
* **Action Required Alert**: High-priority alert banner detailing major emerging customer concerns, rating impacts, and direct links to the Triage Desk.
* **AI Weekly Brief**: Automatically summarizes core positive feedback and negative friction points in clear, executive text.

### 2. Interactive Product Health Desk
* **Health Filter**: Filter products by their rating status (*Healthy*, *Stable*, or *At Risk*).
* **Sentiment Drilldown**: Click *"Drill Down Sentiment"* on any product card to immediately expose a detailed review breakdown showing specific praise (Radiance, Absorbing texture) and complaints (Dropper seal leak, shipping delay).

### 3. Issue Triage Desk
* **Priority Tracking**: Flags critical issues (e.g., delivery delays up 22%) with timeline and target SKU indicators.
* **SLA Action Checklist**: A checkable task list allowing owners to manage resolution workflows. Checking items dynamically recalculates and updates the resolution progress bar.
* **Customer Evidence Feed**: Lists review quotes that triggered the alert, giving immediate context to the issue.

### 4. Aspect-Based Customer Voice Search
* **Keyword Search**: Instant client-side search across review text.
* **Multi-Filter Tool**: Filter the review feed by **Platform** or **Star Ratings**.
* **AI Detected Themes**: Clickable filter chips (*Product Quality*, *Premium Packaging*, *Delivery Delays*) that instantly isolate matching reviews.

### 5. AI Opportunity Finder & ROI Calculator
* **Mini SKU Opportunity**: Identifies travel-size SKU demands (+280% growth) with target phase launch timelines.
* **Live Revenue Calculator**: Interactive price and unit sales volume sliders that estimate monthly and annual incremental revenue potential.

### 6. Conversational AI Analyst Copilot
* **Natural Language Chat**: Allows brand owners to query reviews conversational style.
* **Suggested Question Chips**: Quick prompt buttons to instantly fetch key ratings risks, Sunscreen summaries, and priority actions.
* **Animated Thinking State**: Simulates AI database queries using typing indicator animations before outputting structured answers.

---

## 🛠️ Technology Stack & Architecture

* **UI Design**: Modern glassmorphic dark theme (`backdrop-filter`), linear gradients, Outfit headers, Inter body typography, and responsive SVG icons.
* **Styling**: Tailored Tailwind CSS (via CDN) combined with customized CSS variables and CSS keyframe animations.
* **Single Page Application (SPA)**: Custom client-side router in JavaScript that handles panel transitions without page reloads.
* **Client-side Filtering & State**: Vanilla JS search filters, checklist progress calculators, and calculator sliders.

---

## 🏃‍♂️ How to Run Locally

Since the project is built on standard web technologies, there are **no dependencies or installation steps required**.

1. Clone this repository:
   ```bash
   git clone https://github.com/Suraj190805/Revlytics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Revlytics
   ```
3. Open `index.html` in your web browser:
   * **Mac**: `open index.html`
   * **Windows**: Double-click `index.html` in File Explorer.