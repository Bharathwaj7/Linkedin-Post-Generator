# 🚀 LinkedIn Post Generator using Lama 3.2, LangChain & Streamlit

A smart LinkedIn Post Generator tool built with ❤️ using Lama 3.2 (Open-Source LLM), LangChain, Streamlit, and Gro for prompt optimization.

This project helps LinkedIn influencers like *Muskan Honda* (Mental Health & Job Search Creator with 83K+ followers) effortlessly generate posts matching their unique style & voice 🎯.

---

## ✨ Features

- 📝 Auto-generate LinkedIn posts based on past content
- 🎯 Select Topic, Language & Post Length
- 🖥️ Interactive UI using Streamlit
- ⚙️ Modular & Scalable Code Structure
- 🤖 LLM-Powered Content Generation

---

## 🛠️ Project Workflow

### 1️⃣ Data Collection
- 📦 Scraped & structured historical LinkedIn posts
- 🗂️ Stored data in JSON format for easy processing

### 2️⃣ Data Pre-processing
- 🔖 Added metadata:
  - Topics
  - Tags
  - Language
  - Tone
  - Post Length (Short / Medium / Long)
- 🧹 Cleaned & standardized data for LLM usage

### 3️⃣ Post Generation Logic
- 📚 Dynamic topic library based on influencer style
- 🧩 User Inputs:
  - Topic selection
  - Language preference (English / Hinglish)
  - Post Length
- 🤖 Generated posts using Lama 3.2 + LangChain + Gro

### 4️⃣ Architecture Overview
Two core stages:

- 🏗️ Pre-processing Stage → Clean & enrich influencer data
- ⚡ Generation Stage → Dynamic prompting & LLM response

> *(Optional: Integrated Bright Data for latest content scraping)*

---

## 🖥️ Streamlit UI

Simple & clean interface with:

- 🔽 Influencer Selection Dropdown
- 🗒️ Topic Selector
- 🌐 Language Toggle
- 📏 Post Length Selector
- 🔘 Generate Post Button

---

## 🧪 Testing & Debugging

- 🔄 Iterative testing with multiple influencers
- 🪄 Optimized prompt engineering for tone accuracy
- 🕵️‍♂️ Validated generated posts for quality & consistency

---

## 🧩 Modular Code Structure

| Module | Description |
|--------|-------------|
| `load_posts()` | Load & parse influencer data |
| `filter_topics()` | Filter topics dynamically |
| `generate_prompt()` | Create adaptive LLM prompts |
| `generate_post()` | Generate final LinkedIn-ready post |

---

## 🚀 Final Output

- 🎯 Personalized LinkedIn post generation
- 🔧 Fully adjustable parameters (Style, Tone, Length, Language)
- 🗂️ Ready-to-publish LinkedIn content in seconds!

---

## 💡 Future Enhancements
- 🎭 Influencer-style fine-tuning
- 🕹️ More customization controls
- 🌐 Multi-platform content generator (Twitter, Instagram)

---

## 📸 Demo Preview
> *Coming Soon...*

---

Made with ❤️ by *Bharathwaj*
