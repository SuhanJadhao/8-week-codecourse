AetherOS: Full-Stack AI Engineering Sprint

0. The Mission

To transform from a frontend novice to a Full-Stack AI Engineer in 56 days. This repository contains the curriculum tracker and the evolving codebase for AetherOS, a world-class AI-powered SaaS application.

Standard: BITS Pilani Engineering Excellence. No shortcuts. No fluff.

1. Technical Stack (The Modern AI Stack)

This project eschews legacy MERN patterns for high-velocity, production-ready tooling:

Framework: Next.js 15+ (App Router, Server Actions, React Server Components)

Styling: Tailwind CSS + Shadcn UI

Backend-as-a-Service: Supabase (PostgreSQL, Auth, RLS, Vector)

AI Intelligence: Vercel AI SDK + Claude 3.5 Sonnet

Deployment: Vercel

AI-Native Tooling: - Windsurf: Primary IDE for agentic coding.

v0.dev: Generative UI for rapid component prototyping.

2. Repository Structure

├── app/                # Next.js App Router (The heart of AetherOS)
├── components/         # Atomic UI components (Shadcn + Custom)
├── hooks/              # Reusable React logic
├── lib/                # Shared utilities (Supabase client, AI config)
├── supabase/           # Migrations, SQL schemas, and RLS policies
└── public/             # Static assets


3. Getting Started

Prerequisites

Node.js 20.x or higher

Bun or pnpm (Preferred package managers)

A dedicated Supabase Project

Anthropic API Key (for Claude 3.5 Sonnet)

Installation

Clone the repository.

Install dependencies:

npm install


Configure Environment Variables (.env.local):

NEXT_PUBLIC_SUPABASE_URL=your_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
ANTHROPIC_API_KEY=your_api_key


Run the development server:

npm run dev


4. The 8-Week Protocol

Execution is tracked via the internal App.jsx curriculum dashboard.

Week 1-2: Frontend Architecture & UI density.

Week 3-4: Secure Data Persistence & LLM Integration.

Week 5-6: RAG (Knowledge Retrieval) & Autonomous Agents.

Week 7-8: Multi-agent Systems & Production Hardening.

5. Engineering Standards

Strict Typing: No any. Use TypeScript interfaces for everything.

Component Isolation: Keep Client Components at the leaf nodes. Use Server Components for data fetching.

Atomic Commits: Commit every time a daily milestone is reached.

AI Workflow: Use Windsurf to explain why code is written, not just how.

"Discomfort is the prerequisite for engineering mastery. If the code is easy, you aren't learning." — Mentor's Console
