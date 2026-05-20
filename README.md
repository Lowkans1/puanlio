# 📈 Puanlıo - Hyperlocal Gamified Social & B2B SaaS Platform

*Note: The source code of this repository is private due to commercial, proprietary, and data privacy reasons. Below is the comprehensive product documentation, business model, and architectural overview.*

## 🎯 Product & Business Impact (The MIS Perspective)
Puanlıo is an all-in-one, location-based social ecosystem and B2B SaaS platform designed to drive foot traffic to local businesses while maximizing user engagement through gamification. 

### 👥 For Consumers (The Social App)
- **Location-Based Discovery:** Users can explore, rate, and review local businesses partitioned by cities using an interactive map interface.
- **Social Connectivity:** Features a real-time friend-tracking map, private direct messaging (DM), city-wide group chats, and the ability to create/join social activities.
- **Gamified Loyalty (XP & Rewards):** Visiting partner venues and checking in awards users with XP. Accumulated XP can be redeemed for digital rewards and E-Pins (currently in active development).
- **Exclusive Discounts:** Users unlock dynamic discount vouchers provided directly by local venues.

### 🏢 For Businesses (The B2B Dashboard)
- **AI-Powered B2B Dashboard:** Local merchants get access to a dedicated dashboard that leverages AI to analyze customer sentiment, track foot traffic trends, and optimize marketing campaigns.

---

## 🧠 AI-Accelerated Engineering Workflow
The entire development lifecycle of Puanlıo heavily relied on modern, AI-native engineering methodologies to ensure rapid prototyping and architecture reliability:
- **Rapid Prototyping:** Used LLMs to efficiently scaffold complex geospatial database structures (for map coordinates), structure the XP/reward algorithm logic, and build responsive dashboard layouts.
- **Verification & Edge-Case Testing:** Automated rigorous unit test case generation using AI tools, specifically verifying the security of the messaging systems and the precision of the location-based check-in logic.
- **Pragmatic Problem Solving:** Handled real-time data synchronization challenges (WebSockets for DMs and map updates) by pairing with AI assistants to reason through complex state management trade-offs from first principles.

---

## 🛠️ Tech Stack & High-Level Architecture
- **Frontend / Client Experience:** React Ecosystem, Responsive Mobile-First Design, Interactive Maps API.
- **Backend & Real-Time:** Node.js, WebSockets (for active DMs & live city chats).
- **AI Integration:** LLMs / OpenAI APIs for B2B predictive analytics and sentiment analysis.
- **Workflows & Tools:** Git, GitHub Copilot, ChatGPT (Advanced Prompt Engineering).
