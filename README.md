Edidiong David — AI Prompt Engineering Portfolio

AI Prompt Engineer · LLM Systems & Agent Design · Building for Nigerian and African Markets

Lagos, Nigeria · @iEddydavid · LinkedIn · edidiongdavid187@gmail.com

Who I Am

I am an AI Prompt Engineer specialising in production grade LLM systems, RAG pipelines, and multi-step AI agents designed specifically for Nigerian and African business contexts. I currently work remotely as an ai agent beta tester at Multichainz, an early stage AI agent platform, and I am completing advanced AI engineering training while actively building systems that reflect the realities of doing business in Nigeria; local language fluency, regulatory awareness, and the kind of evaluation discipline that separates deployed systems from impressive demos.

My goal is straightforward: to become one of the most capable AI engineers in Nigeria, known for building systems that actually work for African users and beyond, not just systems that work in +a Western default context.

What This Portfolio Demonstrates

Every project in this repository is a complete, professional artifact; not a tutorial follow along, not a notebook exercise. Each one demonstrates a specific layer of production AI engineering capability.

Designing AI agent systems with tool boundaries, planning loops, and failure mode handling
Building RAG pipelines with documented chunking decisions and cross-language retrieval testing
Writing production system prompts with injection defense, escalation logic, and Nigerian market localization
Building evaluation infrastructure: golden datasets, scoring rubrics, and LLM-as-judge prompts
Translating technical AI systems into client facing business language
Featured Project: Zara Pay AI Customer Support Bot

The most complete artifact in this portfolio. A full production specification for a Nigerian fintech AI support system, graded at Distinction level (97/100).

Zara Pay is a Nigerian mobile first fintech serving users aged 18 to 35 across Lagos, Abuja, and Port Harcourt. This specification covers everything a developer and compliance team needs to implement a production ready AI support bot, from architecture decision through evaluation framework and client summary.

What the specification contains

Architecture decision — RAG combined with a detailed system prompt and tool calling, with full justification referencing knowledge volatility, CBN regulatory change frequency, and cost constraints for a mobile-first Nigerian user base.

Full system prompt — six-section format covering identity, scope, tone, escalation, injection defense, and a worked example in Nigerian Pidgin. Includes the Transfer Status Integrity Rule, a mandatory accuracy safeguard preventing the bot from falsely confirming interbank credits.

Five tool definitions — get_wallet_balance, get_transaction_status, get_vault_details, check_airtime_or_bill_status, escalate_to_human — each with explicit when-to-use and when-NOT-to-use boundaries, parameters, and cross-tool referencing rules.

Golden dataset — eight test cases covering happy path, Pidgin language variety, emotional intensity, boundary testing, adversarial prompt injection, escalation verification, airtime status, and account restriction.

Scoring rubric — three-criterion rubric (Accuracy, Empathy, Action) with Zara Pay specific score definitions at every level. Includes a production gate: responses scoring below 7 out of 15 must not be deployed.

LLM-as-judge prompt — ready-to-use judge prompt with four Zara Pay-specific critical rules, including a hard floor of Action = 1 for any fraud escalation failure.

Failure mode analysis — identifies false transfer confirmation as the highest-risk failure mode, with regulatory, reputational, and customer harm analysis, and the exact system prompt addition that prevents it.

Client-facing summary — one page written for a non-technical CEO, leading with business outcomes and three measurable success metrics.

Reference Book — Prompt Engineering and Generative AI

A 21,000-word, 50-chapter technical reference covering the full prompt engineering and generative AI curriculum applied to Nigerian business contexts.

13 parts covering LLM fundamentals, tokenization and the Nigerian language cost problem, transformer architecture, the four core prompting techniques, advanced techniques including ReAct and ToT, RAG end to end, AI agent design, multi-agent systems, evaluation frameworks, AI safety, fine-tuning and PEFT/LoRA, performance optimization, and building reusable systems for Nigerian prompt engineers.

Every concept is applied to Nigerian business examples rather than the Western defaults that dominate most AI education content.

Interactive Simulations

Three standalone HTML simulations running in any browser with no internet connection required.

Tokenizer and Attention Explorer — type any text and watch real-time tokenization including the Nigerian-language example showing why Pidgin costs more tokens than equivalent English. Includes a click-through attention weight visualisation.

RAG Pipeline Simulator — a Nigerian HR policy document queryable with real questions. Watch retrieval scores, chunk selection, prompt assembly, and grounded answer generation step by step. Includes a question that exposes a genuine document gap.

AI Agent Simulator — a Nigerian fintech support agent running the Think-Act-Observe loop across four scenarios including the fraud case where the agent correctly stops itself from taking unauthorised action.

RAG Pipeline — Nigerian HR Policy

A documented RAG architecture build for a Nigerian HR policy knowledge base, answering employee queries in both formal English and Nigerian Pidgin. Chunking decisions documented iteratively as an evidence-based engineering record. Retrieval tested across Pidgin and formal English inputs for equivalent underlying queries.

Ogabeq Fintech Agent System

A complete multi-tool AI customer support agent for a Nigerian fintech company. Six production-ready tool definitions with explicit boundary rules. Complete system prompt with injection defence. Four simulated scenarios. Full evaluation framework including golden dataset, rubric, and LLM-as-judge prompt.

Technical Skills

Prompting — zero-shot, few-shot, chain-of-thought, role prompting, ReAct, Tree of Thought, self-consistency, prompt chaining, XML structured outputs

Agent systems — tool definition and boundary design, orchestrator-worker multi-agent patterns, planning loop design, failure mode handling

RAG — chunking strategy, overlap design, embedding pipeline, semantic retrieval, grounding, hallucination reduction

Evaluation — golden dataset construction, scoring rubric design, LLM-as-judge, adversarial and bias testing

Safety — prompt injection defence, escalation architecture, regulatory awareness for Nigerian fintech

Models and APIs — Claude API, OpenAI API, Mistral via Ollama, LangChain concepts

Fine-tuning — PEFT and LoRA concepts, dataset format, RAG versus fine-tuning decision framework

Nigerian market — Pidgin and code-switched language handling, CBN regulatory context, BVN/NIN processes, cultural localisation in system prompts

Currently Building

Completing the Udacity AI and Machine Learning curriculum. Actively seeking opportunities to contribute to AI agent systems in Nigerian fintech, logistics, and productivity tooling.

Connect

Email: edidiongdavid187@gmail.com Phone: +234 810 370 9979 LinkedIn: linkedin.com/in/edidiong-david-b98b3520a Twitter/X: @iEddydavid

All projects in this repository were built as part of a structured prompt engineering programme in 2024, applying production AI engineering discipline to real Nigerian business contexts.
