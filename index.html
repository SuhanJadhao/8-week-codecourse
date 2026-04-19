<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AetherOS | Curriculum Tracker</title>
    <script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=JetBrains+Mono:wght@400;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .font-mono { font-family: 'JetBrains+Mono', monospace; }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0a0a0a; }
        ::-webkit-scrollbar-thumb { background: #262626; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #404040; }
    </style>
</head>
<body class="bg-neutral-950 text-neutral-200">
    <div id="root"></div>

    <script type="text/babel">
        const { useState, useMemo, useEffect } = React;

        // Custom Icon Component to handle Lucide in CDN mode
        const Icon = ({ name, className }) => {
            useEffect(() => {
                if (window.lucide) {
                    window.lucide.createIcons();
                }
            }, [name]);
            return <i data-lucide={name} className={className}></i>;
        };

        const curriculumData = [
            {
                week: 1,
                title: "Frontend Architecture & Declarative State",
                icon: "layout",
                days: [
                    { day: 1, objective: "Next.js Initialization & Project Scaffolding", steps: "Install Node.js. Execute `npx create-next-app@latest aetheros --typescript --tailwind --app`. Configure Windsurf workspace settings.", milestone: "Establishment of the local development environment." },
                    { day: 2, objective: "Component Composition & JSX Syntax", steps: "Deconstruct a static HTML dashboard into isolated React components. Instruct Cascade to explain JSX constraints.", milestone: "Transitioning from monolithic HTML to modular UI architecture." },
                    { day: 3, objective: "Unidirectional Data Flow & Props", steps: "Define TypeScript interfaces for component parameters. Pass simulated telemetry data to child metric cards.", milestone: "Understanding data propagation and strict type definitions." },
                    { day: 4, objective: "State Management via React Hooks", steps: "Implement useState to manage interactive elements. Replace imperative DOM targeting with declarative state binding.", milestone: "Grasping the React Virtual DOM lifecycle." },
                    { day: 5, objective: "Server vs. Client Components (RSCs)", steps: "Refactor to strictly isolate Client Components. Move interactivity to the leaf nodes of the tree.", milestone: "Mastering the Next.js rendering paradigm." },
                    { day: 6, objective: "File-System Routing & Dynamic Segments", steps: "Create nested routes. Implement persistent navigation layouts using app/layout.tsx.", milestone: "Utilizing server-side routing and handling dynamic URLs." },
                    { day: 7, objective: "Data Fetching Basics & Vercel Deployment", steps: "Simulate an async fetch within a Server Component. Push to GitHub and trigger Vercel deployment.", milestone: "End-to-end understanding of the Next.js CI/CD pipeline." }
                ]
            },
            {
                week: 2,
                title: "Rapid Prototyping & Generative Interfaces",
                icon: "layers",
                days: [
                    { day: 8, objective: "Utility-First Styling with Tailwind CSS", steps: "Convert legacy CSS to Tailwind utilities. Understand responsive modifiers and flexbox/grid.", milestone: "Rapid, context-free styling directly within components." },
                    { day: 9, objective: "Prompt Engineering for v0.dev", steps: "Prompt v0.dev to generate the core AetherOS dashboard using aesthetic modifiers.", milestone: "Translating UX requirements into natural language prompts." },
                    { day: 10, objective: "Integrating Shadcn UI Primitives", steps: "Execute `npx shadcn-ui@latest init`. Import generated v0.dev components.", milestone: "Establishing a customizable, accessible design system." },
                    { day: 11, objective: "Constructing Complex Layouts", steps: "Stitch atomic components together for the primary command center.", milestone: "Building scalable UI architectures for dense data." },
                    { day: 12, objective: "Interactive Modals and Form State", steps: "Implement accessible forms for agent configuration using Shadcn UI.", milestone: "Handling user input while maintaining accessibility." },
                    { day: 13, objective: "Theming, Dark Mode, and CSS Variables", steps: "Configure next-themes. Map AetherOS brand colors in globals.css.", milestone: "Implementing persistent, system-aware theming." },
                    { day: 14, objective: "UI Codebase Refactoring via Windsurf", steps: "Instruct Windsurf to clean up v0.dev output and enforce strict TS interfaces.", milestone: "Sanitizing architecture to prevent technical debt." }
                ]
            },
            {
                week: 3,
                title: "Data Persistence & Multi-Tenant Security",
                icon: "database",
                days: [
                    { day: 15, objective: "Relational Database Fundamentals", steps: "Study PostgreSQL concepts. Design schema: users, organizations, agents, logs.", milestone: "Transitioning mental models to relational integrity." },
                    { day: 16, objective: "Supabase Project Initialization", steps: "Provision Supabase project. Create tables via SQL. Pull schema locally via CLI.", milestone: "Establishing remote DB and syncing environment." },
                    { day: 17, objective: "Server-Side Authentication Setup", steps: "Install @supabase/ssr. Configure Next.js server actions for secure sessions.", milestone: "Implementing modern, secure session handling." },
                    { day: 18, objective: "Building the Authentication Interface", steps: "Utilize Shadcn UI for login flows. Wire components to server Auth endpoints.", milestone: "Managing auth state across the frontend." },
                    { day: 19, objective: "Implementing Row Level Security (RLS)", steps: "Write PostgreSQL RLS policies ensuring isolation between organization tenants.", milestone: "Securing the DB against cross-tenant exposure." },
                    { day: 20, objective: "Secure Data Fetching and Mutations", steps: "Create Server Actions to safely insert/retrieve configurations.", milestone: "Executing secure database transactions." },
                    { day: 21, objective: "Route Protection and Middleware", steps: "Implement Next.js middleware to verify sessions and redirect accordingly.", milestone: "Hardening routes and centralized access control." }
                ]
            },
            {
                week: 4,
                title: "Vercel AI SDK & Claude 3.5 Sonnet",
                icon: "brain",
                days: [
                    { day: 22, objective: "LLM Mechanics and Prompt Engineering", steps: "Study tokens, context windows, temperature, and system prompts.", milestone: "Understanding statistical AI and output guidance." },
                    { day: 23, objective: "API Integration via generateText", steps: "Install ai and @ai-sdk/anthropic. Construct API route for Claude.", milestone: "Executing deterministic AI text generation requests." },
                    { day: 24, objective: "Real-Time Streaming", steps: "Implement conversational interface using streamText (server) and useChat (client).", milestone: "Managing real-time data to overcome HTTP timeouts." },
                    { day: 25, objective: "Enforcing Structured Outputs", steps: "Force LLM to output JSON conforming to Zod schema via useObject.", milestone: "Converting probabilistic text into deterministic inputs." },
                    { day: 26, objective: "Context Window Management", steps: "Persist conversation histories in Supabase to hydrate the LLM context window.", milestone: "Managing context limits and token costs." },
                    { day: 27, objective: "Generative UI and RSC Streaming", steps: "Utilize streamUI to stream dynamic React components directly from response.", milestone: "Blending rendering with AI generation." },
                    { day: 28, objective: "Telemetry and Vercel AI Gateway", steps: "Route requests through AI Gateway. Monitor usage and rate limits.", milestone: "Hardening AI infrastructure for production." }
                ]
            },
            {
                week: 5,
                title: "Knowledge Retrieval & RAG Architecture",
                icon: "book-open",
                days: [
                    { day: 29, objective: "Vector Math & Semantic Similarity", steps: "Study high-dimensional vector spaces and text-to-numerical arrays.", milestone: "Comprehending mathematics of semantic search." },
                    { day: 30, objective: "Database Prep via pgvector", steps: "Enable pgvector in Supabase. Create table with vector columns.", milestone: "Configuring database for similarity operations." },
                    { day: 31, objective: "Text Ingestion and Chunking", steps: "Build Node utility to ingest manuals and split into overlapping chunks.", milestone: "Preparing unstructured data for embeddings." },
                    { day: 32, objective: "Generating Embeddings", steps: "Utilize embedding models to generate vectors for indexed chunks.", milestone: "Translating text into vector space." },
                    { day: 33, objective: "Executing Vector Searches", steps: "Write custom SQL function using cosine similarity for pgvector index.", milestone: "Executing high-speed spatial searches." },
                    { day: 34, objective: "Orchestrating the RAG Pipeline", steps: "Wire: Query -> Embed -> Search -> Retrieve -> Inject -> Generate.", milestone: "Establishing end-to-end RAG architecture." },
                    { day: 35, objective: "Advanced RAG: Hybrid Search", steps: "Implement hybrid search (keyword + vector) and refine chunking.", milestone: "Fine-tuning knowledge retrieval accuracy." }
                ]
            },
            {
                week: 6,
                title: "Multi-Step Tools & Autonomous Agents",
                icon: "terminal",
                days: [
                    { day: 36, objective: "Defining Tool Schemas", steps: "Define custom tools in generateText. Type schemas rigorously with Zod.", milestone: "Teaching LLM to format responses for execution." },
                    { day: 37, objective: "Intercepting Tool Calls", steps: "Implement tool querying Supabase for live metrics based on LLM prompts.", milestone: "Bridging probabilistic reasoning and APIs." },
                    { day: 38, objective: "Multi-Step Orchestration", steps: "Configure maxSteps. Build sequences where LLM evaluates results.", milestone: "Implementing autonomous chains of thought." },
                    { day: 39, objective: "Parallel Tool Execution", steps: "Enable parallel tools and stream execution status to UI.", milestone: "Optimizing latency and providing UI transparency." },
                    { day: 40, objective: "ToolLoopAgent Architecture", steps: "Implement pattern combining deterministic branching with LLM decisions.", milestone: "Designing reliable guardrails around AI models." },
                    { day: 41, objective: "Advanced Interactions: Computer Use", steps: "Explore Anthropic Computer Use for system interaction.", milestone: "Extending agent capabilities into systemic levels." },
                    { day: 42, objective: "Error Recovery Loops", steps: "Build feedback loops to catch tool errors and retry with adjusted params.", milestone: "Enhancing robustness of AI operations." }
                ]
            },
            {
                week: 7,
                title: "Architecting Distributed Intelligence",
                icon: "rocket",
                days: [
                    { day: 43, objective: "Finalizing Distributed Schema", steps: "Optimize Supabase schema to support simulated grid devices.", milestone: "Architecting data layer for massive scale." },
                    { day: 44, objective: "Defining Agent Personas", steps: "Create distinct AI personas for Diagnostic and Optimization roles.", milestone: "Segmenting complex tasks into specialized roles." },
                    { day: 45, objective: "Durable Execution via Workflows", steps: "Implement Vercel Workflows for long-running agent tasks.", milestone: "Managing resilient background processes." },
                    { day: 46, objective: "Multi-Agent Collaboration", steps: "Build message delivery system for agents to pass structured data.", milestone: "Establishing communication between entities." },
                    { day: 47, objective: "Hydrating Agent Contexts", steps: "Develop workspace hydration to inject system state into agent memory.", milestone: "Providing agents an accurate world-view." },
                    { day: 48, objective: "Command Center UI", steps: "Build dashboard visualizing agent activity and system health.", milestone: "Translating orchestration loops into actionable UI." },
                    { day: 49, objective: "Human-in-the-Loop Gates", steps: "Implement approval gates for destructive actions via Workflows.", milestone: "Enforcing safety and human control." }
                ]
            },
            {
                week: 8,
                title: "Production Optimization & Deployment",
                icon: "shield",
                days: [
                    { day: 50, objective: "Prompt Caching & Cost Optimization", steps: "Configure ephemeral prompt caching to reduce API overhead.", milestone: "Engineering for financial viability." },
                    { day: 51, objective: "Telemetry and Observability", steps: "Analyze AI Gateway metrics and log token usage per tenant.", milestone: "Gaining deep operational visibility." },
                    { day: 52, objective: "Security Hardening", steps: "Audit RLS policies and implement injection detection.", milestone: "Protecting against adversarial attacks." },
                    { day: 53, objective: "Systematic AI Evaluation", steps: "Implement frameworks to systematically grade LLM outputs.", milestone: "Transitioning to automated QA for AI." },
                    { day: 54, objective: "CI/CD Pipeline Integration", steps: "Establish GitHub Actions for auto-linting and type checks.", milestone: "Automating software deployment lifecycle." },
                    { day: 55, objective: "Global Deployment", steps: "Link GitHub to Vercel and configure production environments.", milestone: "Launching AetherOS globally on edge infrastructure." },
                    { day: 56, objective: "Final Architectural Audit", steps: "Conduct end-to-end review of the entire system codebase.", milestone: "Finalizing transition to Full-Stack AI Engineer." }
                ]
            }
        ];

        const mentorQuotes = [
            "BITSians don't watch tutorials. We read documentation, break things, and rebuild them stronger.",
            "If you're copy-pasting code without understanding the underlying state mechanics, you're a typist, not an engineer.",
            "Windsurf is an exoskeleton, not a wheelchair. You must architect; the AI just types.",
            "Are you struggling? Good. Discomfort is the prerequisite for engineering mastery.",
            "Don't tell me what your app is supposed to do. Show me the deployment link.",
            "Technical debt is a tax levied on the lazy. Enforce strict types today, or bleed tomorrow."
        ];

        function App() {
            const [completedDays, setCompletedDays] = useState(new Set());
            const [activeWeek, setActiveWeek] = useState(1);
            const [quoteIndex, setQuoteIndex] = useState(0);

            const toggleDay = (dayNum) => {
                setCompletedDays(prev => {
                    const newSet = new Set(prev);
                    if (newSet.has(dayNum)) newSet.delete(dayNum);
                    else {
                        newSet.add(dayNum);
                        setQuoteIndex(Math.floor(Math.random() * mentorQuotes.length));
                    }
                    return newSet;
                });
            };

            const progress = Math.round((completedDays.size / 56) * 100);
            const activeWeekData = curriculumData.find(w => w.week === activeWeek);
            
            const weekProgress = (wNum) => {
                const wDays = curriculumData.find(w => w.week === wNum).days;
                const done = wDays.filter(d => completedDays.has(d.day)).length;
                return Math.round((done / 7) * 100);
            };

            return (
                <div className="flex flex-col lg:flex-row h-screen bg-neutral-950 overflow-hidden">
                    {/* Sidebar */}
                    <div className="w-full lg:w-80 bg-neutral-900 border-r border-neutral-800 flex flex-col shrink-0">
                        <div className="p-6 border-b border-neutral-800">
                            <div className="flex items-center gap-2 mb-2">
                                <Icon name="cpu" className="w-6 h-6 text-emerald-500" />
                                <h1 className="text-xl font-bold text-white">AetherOS Core</h1>
                            </div>
                            <p className="text-[10px] text-neutral-500 font-mono tracking-widest uppercase mb-4">Engineering Protocol // BITS Pilani</p>
                            <div className="space-y-2">
                                <div className="flex justify-between text-xs font-mono">
                                    <span className="text-neutral-400">Total Progress</span>
                                    <span className="text-emerald-500">{progress}%</span>
                                </div>
                                <div className="h-1.5 w-full bg-neutral-800 rounded-full overflow-hidden">
                                    <div className="h-full bg-emerald-500 transition-all duration-500" style={{width: `${progress}%`}}></div>
                                </div>
                            </div>
                        </div>
                        <div className="flex-1 overflow-y-auto p-4 space-y-1">
                            {curriculumData.map(w => (
                                <button key={w.week} onClick={() => setActiveWeek(w.week)} 
                                    className={`w-full text-left p-3 rounded-lg flex items-center gap-3 transition-all ${activeWeek === w.week ? 'bg-neutral-800 text-white shadow-lg' : 'text-neutral-500 hover:bg-neutral-800/40'}`}>
                                    <div className={`p-2 rounded-md ${activeWeek === w.week ? 'bg-emerald-500/10 text-emerald-500' : 'bg-neutral-800'}`}>
                                        <Icon name={w.icon} className="w-4 h-4" />
                                    </div>
                                    <div className="flex-1 min-w-0">
                                        <div className="text-xs font-bold uppercase tracking-tight">Week {w.week}</div>
                                        <div className="text-[10px] truncate opacity-60">{w.title}</div>
                                    </div>
                                    {weekProgress(w.week) === 100 && <Icon name="check-circle-2" className="w-4 h-4 text-emerald-500" />}
                                </button>
                            ))}
                        </div>
                    </div>

                    {/* Main */}
                    <div className="flex-1 flex flex-col overflow-hidden">
                        <div className="p-6 bg-neutral-900/30 border-b border-neutral-800 flex items-center gap-4">
                            <div className="p-2 bg-neutral-800 rounded border border-neutral-700">
                                <Icon name="zap" className="w-5 h-5 text-yellow-500" />
                            </div>
                            <div className="font-mono text-sm text-emerald-400">
                                <span className="text-neutral-500 mr-2">MENTOR:</span>
                                {'>'} {mentorQuotes[quoteIndex]}
                            </div>
                        </div>

                        <div className="flex-1 overflow-y-auto p-6 lg:p-12">
                            <div className="max-w-3xl mx-auto">
                                <div className="mb-10">
                                    <span className="text-emerald-500 font-mono text-xs font-bold px-2 py-1 bg-emerald-500/10 border border-emerald-500/20 rounded mb-4 inline-block">MODULE 0{activeWeek}</span>
                                    <h2 className="text-4xl font-bold text-white mb-2">{activeWeekData.title}</h2>
                                    <div className="flex items-center gap-4 text-neutral-500 text-sm">
                                        <div className="flex items-center gap-1"><Icon name="clock" className="w-4 h-4" /> 7 Days</div>
                                        <div className="flex items-center gap-1"><Icon name="activity" className="w-4 h-4" /> {weekProgress(activeWeek)}% Done</div>
                                    </div>
                                </div>

                                <div className="space-y-6">
                                    {activeWeekData.days.map(d => (
                                        <div key={d.day} onClick={() => toggleDay(d.day)}
                                            className={`p-5 rounded-xl border transition-all cursor-pointer group ${completedDays.has(d.day) ? 'bg-neutral-900/40 border-emerald-900/30 opacity-60' : 'bg-neutral-900 border-neutral-800 hover:border-neutral-700'}`}>
                                            <div className="flex items-start justify-between gap-4">
                                                <div className="flex-1">
                                                    <div className="flex items-center gap-2 mb-2">
                                                        <span className={`text-[10px] font-mono px-1.5 py-0.5 rounded ${completedDays.has(d.day) ? 'bg-emerald-500/20 text-emerald-500' : 'bg-neutral-800 text-neutral-400'}`}>DAY {d.day}</span>
                                                        <h3 className={`font-bold text-lg ${completedDays.has(d.day) ? 'text-neutral-400 line-through' : 'text-white'}`}>{d.objective}</h3>
                                                    </div>
                                                    <div className="text-sm text-neutral-400 font-mono bg-black/40 p-3 rounded border border-neutral-800/50 mb-3">
                                                        {d.steps}
                                                    </div>
                                                    <div className="flex items-center gap-2 text-[11px] text-neutral-500">
                                                        <Icon name="target" className="w-3 h-3 text-emerald-500" />
                                                        <span className="font-bold text-neutral-400 uppercase">Milestone:</span> {d.milestone}
                                                    </div>
                                                </div>
                                                <div className={`mt-1 p-1 rounded-full border-2 transition-colors ${completedDays.has(d.day) ? 'bg-emerald-500 border-emerald-500 text-white' : 'border-neutral-700 text-transparent group-hover:border-neutral-500'}`}>
                                                    <Icon name="check" className="w-4 h-4" />
                                                </div>
                                            </div>
                                        </div>
                                    ))}
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            );
        }

        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(<App />);
    </script>
</body>
</html>
