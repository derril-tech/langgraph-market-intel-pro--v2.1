# 🚀 MarketIntel Pro
**Powered by LangGraph + OpenAI**

🌐 **[View Live Application](https://langgraph-market-intel-pro.vercel.app)**

> **Transform competitive research into actionable strategy. Enter a product category, and get a comprehensive competitive analysis with market gaps, feature matrices, and GTM recommendations—powered by AI agents.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![LangGraph](https://img.shields.io/badge/LangGraph-AI_Agents-purple.svg)](https://langchain-ai.github.io/langgraph/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6.svg)](https://www.typescriptlang.org/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

MarketIntel Pro is an intelligent competitive analysis platform that uses a **multi-agent LangGraph workflow** to:

1. **Search Competitors** — Discover and analyze competitor websites via real web search APIs
2. **Extract Intelligence** — Parse pricing, positioning, and feature sets from competitor data
3. **Build Comparison Matrix** — Create normalized feature-by-competitor matrices for side-by-side analysis
4. **Identify Market Gaps** — Detect opportunities where competitors fall short with quantified scores
5. **Generate Strategy** — Produce actionable GTM recommendations based on market intelligence

All delivered through a beautiful, responsive interface with real-time progress tracking.

---

## 🎯 Core Features

### 🤖 **AI-Powered Analysis**
- **Real OpenAI Integration** — GPT-4.1-mini for intelligent analysis and chat assistance
- **Multi-Agent Workflow** — LangGraph orchestrates 5 specialized pipeline nodes
- **Live Web Search** — SerpAPI/Tavily integration for real-time competitor discovery
- **Real-Time Progress** — Step-by-step pipeline execution with live status updates

### 📊 **Rich Visualizations**
- **Interactive Feature Matrix** — Sortable, filterable comparison table with mobile card view
- **Market Gap Analysis** — Prioritized opportunities with coverage scores and impact ratings
- **Competitor Profiles** — Detailed views with pricing, features, and positioning
- **Strategy Playbook** — Comprehensive GTM roadmap with timelines and metrics

### 🎨 **Modern UI/UX**
- **Single-Page Architecture** — Smooth state-driven transitions, no page reloads
- **Dark/Light Mode** — Beautiful theme system with system preference support
- **Mobile-First Design** — Fully responsive with 44px+ touch targets, optimized for all devices
- **Hero Video Backgrounds** — Engaging landing experience with theme-aware videos
- **Micro-Animations** — Smooth transitions and loading states throughout

### 📱 **Full Feature Set**
| Feature | Description |
|---------|-------------|
| 🔍 **Competitive Analysis** | Full market landscape analysis in seconds |
| 📈 **Feature Matrix** | Interactive comparison table with sorting and filtering |
| 🎯 **Gap Detection** | Identified market opportunities with scores |
| 💡 **Strategy Recommendations** | Positioning, pricing, and feature focus suggestions |
| 📄 **Export & Share** | JSON, CSV, Markdown export with shareable links |
| 💬 **AI Chat Assistant** | Ask follow-up questions about your analysis |
| 📚 **Strategy Playbook** | Detailed GTM roadmap generation |
| 📜 **Analysis History** | View, search, and re-run past analyses |
| 🔔 **Notifications** | In-app notifications for job completion |
| 🔗 **Webhooks** | Register webhooks for job events |
| 📊 **Dashboard** | Overview of all analyses with KPIs |

---

## 🏗️ Tech Stack

### **Frontend** ⚛️
| Technology | Purpose |
|------------|---------|
| **Next.js 16** | React 19.2 with App Router, Server Components |
| **TypeScript** | Type-safe development with strict mode |
| **Tailwind CSS** | Utility-first styling with custom design system |
| **shadcn/ui** | Beautiful, accessible component library |
| **next-themes** | Seamless dark/light mode with persistence |
| **Lucide Icons** | Modern, consistent icon set |

### **Backend** 🐍
| Technology | Purpose |
|------------|---------|
| **FastAPI** | High-performance async Python API |
| **LangGraph** | Multi-agent AI orchestration and workflow |
| **OpenAI GPT-4.1** | Intelligent analysis and chat assistance |
| **Pydantic v2** | Data validation and serialization |
| **httpx** | Async HTTP client for webhooks and APIs |

### **Data & Cache** 💾
| Technology | Purpose |
|------------|---------|
| **Supabase** | PostgreSQL with RPC functions for schema isolation |
| **Upstash Redis** | Job queue, caching, and rate limiting |

### **External APIs** 🔌
| API | Purpose |
|-----|---------|
| **SerpAPI / Tavily** | Real-time web search for competitor discovery |
| **OpenAI** | GPT-4.1-mini for analysis and chat |

### **Deployment** 🚀
| Platform | Service |
|----------|---------|
| **Vercel** | Frontend hosting with edge optimization |
| **Railway** | Backend API with Railpack builder |

---

## 📖 User Guide

### Getting Started

1. **Enter Product Category** — e.g., "AI note-taking tools", "DevSecOps platforms"
2. **Add Region/Segment (Optional)** — e.g., "North America", "SMB only"
3. **Configure Options** — Toggle pricing intelligence, add focus areas
4. **Run Analysis** — Watch the LangGraph pipeline execute in real-time
5. **Explore Results** — View matrix, gaps, strategy, and chat with AI

### Understanding Your Results

| Section | What It Shows |
|---------|---------------|
| **Competitors** | List of discovered competitors with URLs, pricing, and positioning |
| **Feature Matrix** | Interactive table comparing features across all competitors |
| **Market Gaps** | Prioritized opportunities with coverage scores (0-100%) |
| **Strategy Recommendations** | Positioning, pricing, and feature focus suggestions |
| **Strategy Playbook** | Detailed GTM roadmap with timelines, metrics, and milestones |

### Pro Tips

- **Be specific** with product categories for better competitor discovery
- **Use focus areas** to guide the analysis toward specific concerns
- **Explore the matrix** by clicking competitors or features for details
- **Ask the AI** follow-up questions for deeper insights
- **Export results** to share with your team or stakeholders
- **Review history** to compare analyses across different categories

---

## 🎨 Design System

### Theme Options
- ☀️ **Light Mode** — Clean, professional interface
- 🌙 **Dark Mode** — Easy on the eyes (default)
- 🖥️ **System** — Follows OS preference

### Color Palette
- **Primary**: Terracotta (#E77A67) — Warm, approachable
- **Secondary**: Mint (#B9F2DA) — Fresh, modern
- **Accent**: Graph (#55C4B4) — Data-focused
- **Neutral**: Charcoal, Beige, Plum — Sophisticated backgrounds

### Mobile Optimization
- ✅ 44px+ touch targets throughout
- ✅ Mobile card view for feature matrix
- ✅ Bottom navigation for easy access
- ✅ Keyboard-aware forms
- ✅ Swipe gestures for modals

---

## 📊 Performance

| Metric | Value |
|--------|-------|
| Analysis Time | ~15-30 seconds |
| Frontend Bundle | Optimized with Next.js 16 |
| Lighthouse Score | 90+ |
| Mobile Ready | ✅ Fully optimized |
| API Response Time | < 200ms (cached) |

---

## 🛡️ Security & Privacy

- ✅ **Schema Isolation** — Multi-tenant database with RPC functions
- ✅ **API Rate Limiting** — Redis-based rate limiting (20 requests/minute)
- ✅ **CORS Protection** — Configured for production domains
- ✅ **Environment Variables** — All secrets stored securely
- ✅ **Input Validation** — Pydantic models for all API inputs
- ✅ **Error Handling** — Comprehensive error handling without exposing internals

---

## 👨‍💻 Creator

**Derril Filemon**

This project showcases expertise in:

- 🤖 **AI/ML Integration** — LangGraph multi-agent workflows, OpenAI GPT-4.1-mini, prompt engineering
- ⚛️ **Modern React** — Next.js 16, React 19.2, Server Components, App Router
- 🐍 **Python Backend** — FastAPI, async/await patterns, Pydantic validation
- 🎨 **UI/UX Design** — Responsive design, accessibility, mobile-first approach, design systems
- ☁️ **Cloud Architecture** — Supabase, Redis, Railway, Vercel, multi-tenant design
- 🔧 **DevOps** — CI/CD, environment management, health checks, monitoring
- 📊 **Data Visualization** — Interactive tables, charts, real-time progress tracking
- 🔐 **Security** — Schema isolation, RPC functions, rate limiting, input validation

---

## 🙏 Acknowledgments

- **[LangGraph](https://langchain-ai.github.io/langgraph/)** — Multi-agent orchestration framework
- **[OpenAI](https://openai.com/)** — GPT-4.1-mini API for intelligent analysis
- **[SerpAPI](https://serpapi.com/)** & **[Tavily](https://tavily.com/)** — Web search integration
- **[Supabase](https://supabase.com/)** — PostgreSQL database and RPC functions
- **[Upstash](https://upstash.com/)** — Redis caching and job queue
- **[Railway](https://railway.app/)** — Backend deployment platform
- **[Vercel](https://vercel.com/)** — Frontend hosting and edge optimization
- **[shadcn/ui](https://ui.shadcn.com/)** — Beautiful, accessible component library
- **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first CSS framework

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[Live Demo](https://langgraph-market-intel-pro.vercel.app) 

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
