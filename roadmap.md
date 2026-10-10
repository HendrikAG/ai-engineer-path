# AI Engineer Path – Setup Guide & 12-Month Roadmap

Oct 9, 2026 · @Hendrik Augustyniak

## How this works

One dedicated Claude Project ("AI Engineer Path") acts as your tutor, curriculum keeper and accountability partner for the next 12 months, at about 5 hours per week.

The plan has six phases, from refreshing the ML foundations behind your master thesis up to building agents, running and fine-tuning models locally, and assembling a portfolio. Alongside the phases run three permanent tracks: staying current with AI news, sharpening your own coding, and mastering Claude itself.

**Honest expectations.** At 5 h/week, 12 months gets you to a solid applied AI Engineer level: you will understand how models work, build real LLM apps and agents, and have a portfolio to show. Getting hired at Google-level companies usually needs more on top: strong hand-written coding (data structures, algorithms), system design interviews, and visible work. Plan for 12 months of building the base, then 3 to 6 months of focused interview preparation.

**One rule that matters most:** write more code yourself than you have since 2024. Use Claude to explain, review and unblock, not to type everything for you. Interviews and real understanding both depend on it.

## Setting up the Claude Project

The setup takes about 20 minutes and only has to be done once.

1. In claude.ai, open **Projects** and create a new project named **AI Engineer Path**.
2. Paste the text from **Project instructions** (next section) into the project's instructions field.
3. Add two knowledge files: **Learner profile** and **Progress log** (contents in the section after). Also export this doc as Markdown or PDF and add it, so Claude always has the roadmap.
4. Make sure memory is on for the project, so Claude can carry context between chats. The progress log stays the reliable anchor either way.
5. Block two recurring slots in your calendar (for example Tuesday 19:00 and Saturday 10:00, 2.5 h each). Claude cannot message you first, so the calendar is your trigger.
6. Start the first chat with: "Start Week 1."

Use one chat per week ("Week 7 – Transformers"), not one endless chat. Long chats get slow and lose focus; the progress log carries continuity between them.

## Project instructions (copy-paste)

Paste the block below unchanged into the project's instructions field.

```markdown
You are my AI tutor, curriculum keeper and accountability coach. My goal: become a hireable AI Engineer within ~12–18 months (long-term option: big tech like Google), studying ~5 hours per week.

Who I am: see "Learner profile". Where I am: see "Progress log". The plan: see the roadmap file.

How to teach me:
- Start every session by checking the progress log, stating where we are, and proposing today's 2–3 concrete goals.
- Explain intuition first, then the math, then code. Connect new topics to things I already know (my LSTM/Random Forest/KNN master thesis, automotive engineering, my work at a software company).
- Make me write the code myself. Give skeletons, hints and reviews, not finished solutions, unless I explicitly ask. If I'm stuck for more than ~15 minutes, give a bigger hint.
- After every topic, quiz me (3–5 questions, mixed difficulty) and use spaced repetition: re-ask things I got wrong in earlier weeks.
- Prefer free, high-quality resources. Name the exact chapter/video, not just the course.
- Be honest when my understanding is shallow. Push back if I want to skip fundamentals.

Motivation & procrastination:
- I tend to procrastinate. Keep every session start tiny: the first task should take under 10 minutes.
- If I come back after a break, don't lecture me. Ask what got in the way, shrink the next step, and restart.
- Celebrate finished milestones briefly and concretely.
- Each week, set ONE small, visible output (a notebook, a repo commit, a short write-up).

End of every session:
- Give me an updated "Progress log" entry (date, what I did, what I understood, what's shaky, next step) in a code block so I can paste it into the knowledge file.
- Tell me the exact first step for next session.

Staying current: when I ask "What's new?", search the web for the most important AI developments of the last 1–2 weeks and explain why they matter for an AI Engineer.
```

## Knowledge files to add

Create these two text files and upload them to the project. Update the progress log every week with the entry Claude gives you at the end of each session.

**File 1: Learner profile**

```markdown
# Learner profile – Hendrik

## Background
- Born 1998, engineer. Previously Software Engineer at Bosch Engineering; mostly understanding/maintaining existing code rather than writing new code.
- Was "AI responsible" for my group at Bosch, but had little time for it.
- Master thesis (2022): AI-based steering models using LSTMs, neural networks, Random Forest, KNN. Used them practically, but basics (math, why things work) are weak.
- Since 2024 mostly coding with GenAI tools (GitHub Copilot, Claude).
- Now working at ForVendi (software products).

## Skill self-assessment (1 = none, 5 = strong)
- Python: 2
- Linear algebra / probability / calculus for ML: 2
- Classical ML: 2
- Deep learning (PyTorch): 1
- Transformers / LLM internals: 1
- LLM APIs, RAG, agents: 2
- Local models: 1
- Data structures & algorithms: 2

## Goals
- Become a hireable AI Engineer (long-term option: big tech).
- Understand the science, not just use tools.
- Build AI apps and agents, including locally on my powerful PC.
- Use AI tools (especially Claude) optimally at work.
- Stay up to date with AI developments.

## Constraints & learning style
- ~5 h/week, ideally 2 fixed sessions.
- I procrastinate and need small steps, visible progress and gentle accountability.

## My hardware
- (fill in: CPU, GPU model + VRAM, RAM, OS)
```

**File 2: Progress log**

```markdown
# Progress log

Current phase: 0 – Setup
Current week: 1
Streak (weeks in a row with ≥1 session): 0

## Shaky topics (re-quiz these)
- 

## Log (newest first)
### Week 1 – YYYY-MM-DD
- Did:
- Understood:
- Shaky:
- Output produced:
- Next first step:
```

Fill in your hardware details (GPU model and VRAM especially): they decide which local models you can run in phases 4 and 5.

## The 12-month roadmap

Six phases take you from foundations to a portfolio; each ends with a small project that proves the phase is done.

&#91;embedded content: AI Engineer roadmap · 7 phases over 12 months\]

### Phase 0 – Setup and first win (weeks 1–2)

- Set up Python, VS Code, Git, a GitHub account for your portfolio, and check your GPU works with PyTorch.
- Tour of Claude features you'll use: Projects, artifacts, Claude Code, web search.
- First win: a tiny script that calls the Claude API and summarizes a text file.

### Phase 1 – Foundations (months 1–2)

- Python for data: NumPy, pandas, matplotlib.
- Math intuition: vectors and matrices, derivatives and gradient descent, probability basics.
- Classical ML done properly: train/test splits, overfitting, metrics, Random Forest and KNN revisited with understanding.
- Resources: Andrew Ng's *Machine Learning Specialization* (Coursera), 3Blue1Brown's *Essence of Linear Algebra* and *Neural Networks* series.
- Project: rebuild a model like the ones in your thesis on a public dataset, with a clean write-up.

### Phase 2 – Deep learning and transformers (months 3–4)

- Backpropagation by hand, PyTorch, CNNs, RNNs and LSTMs (now you'll know why they worked in your thesis).
- Attention, the transformer architecture, tokenization, embeddings.
- Resources: Andrej Karpathy's *Neural Networks: Zero to Hero* (the core of this phase), fast.ai *Practical Deep Learning*, Jay Alammar's *The Illustrated Transformer*.
- Project: build a small GPT from scratch following Karpathy and train it on your own PC.

### Phase 3 – LLM application engineering (months 5–6)

- LLM APIs, prompt engineering, structured outputs, tool use.
- RAG: embeddings, vector databases, chunking, retrieval quality.
- Evaluation: how to measure whether an LLM app is actually good.
- Resources: Anthropic and OpenAI docs and cookbooks, Chip Huyen's *AI Engineering* (book).
- Project: a RAG assistant over real documents, for example your ForVendi product docs, with an evaluation set.

### Phase 4 – Agents and local AI (months 7–8)

- Agent patterns: tool calling, planning, memory, multi-agent setups, when NOT to use agents.
- MCP (Model Context Protocol), Claude Code, the Claude Agent SDK.
- Local models: Ollama, LM Studio, llama.cpp, quantization, what fits in your VRAM.
- Project: a local agent on your PC that automates a real task from your work week.

### Phase 5 – Fine-tuning and deployment (months 9–10)

- Fine-tuning with LoRA/QLoRA on Hugging Face models, data preparation, evaluation before and after.
- Serving and MLOps basics: vLLM, Docker, latency and cost, monitoring.
- Safety and reliability: guardrails, prompt injection, hallucination handling.
- Project: fine-tune a small open model locally for a narrow task and compare it to prompting a large model.

### Phase 6 – Portfolio and career (months 11–12)

- Capstone project that combines phases 3–5, deployed and documented.
- Clean GitHub portfolio, 2–3 public write-ups (blog or LinkedIn).
- Interview prep starts: ML system design (Chip Huyen's *Designing Machine Learning Systems*), coding interviews, reading one paper per week.

The roadmap is a default, not a contract. Claude should speed up or slow down with you each week.

## Continuous tracks

Three tracks run in parallel to the phases, taking about 1 of your 5 weekly hours.

**Staying current (20 min/week).** Once a week, ask the project "What's new?" for a filtered summary. Add one or two sources you skim yourself, for example DeepLearning.AI's *The Batch* newsletter, Simon Willison's blog, or the *Latent Space* podcast. Don't try to follow everything; the goal is to know what matters and why.

**Coding fluency (30 min/week, more from month 9).** Solve small problems without AI help: start with Python exercises, later LeetCode-style problems (easy, then medium). This is the gap most likely to block a big-tech interview, so it grows in phase 6.

**Claude mastery (built in).** You'll learn Claude by using it in every phase: Projects and knowledge (now), the API and prompt engineering (phase 3), tool use, MCP, Claude Code and the Agent SDK (phase 4). Once a month, ask the project for one Claude feature you're not using yet and try it at work.

## Weekly rhythm and starter prompts

Two fixed sessions plus a short review make up the 5 hours.

| Slot | Length | What happens |
| --- | --- | --- |
| Session A (e.g. Tue evening) | 2 h | New concept: explanation, reading or video, first exercises |
| Session B (e.g. Sat morning) | 2.5 h | Hands-on: coding, the phase project, quiz |
| Review (e.g. Sun, any time) | 30 min | "What's new?", update progress log, plan next week |

Prompts to paste into the project:

- **"Start week N."** Claude reads the log and sets today's goals.
- **"Explain \[topic\] like I know engineering but not ML."**
- **"Give me an exercise on \[topic\], don't solve it."**
- **"Review my code: \[paste\]."**
- **"Quiz me on this week, include old weak spots."** (Claude can show interactive quizzes and flashcards.)
- **"I'm stuck and unmotivated. Give me a 10-minute task."**
- **"What's new in AI?"**
- **"End session."** Claude writes the progress log entry and your next first step.

## Motivation safeguards

The plan is built so that starting is easy and stopping is visible.

- **Fixed calendar slots.** Decide once, not every week. Treat them like a meeting with a client.
- **Tiny first step.** Every session starts with a task under 10 minutes; momentum does the rest.
- **Minimum viable session.** On bad days, 25 minutes counts. Keeping the streak matters more than the length.
- **Visible output every week.** A GitHub commit or a short note; your repo history becomes proof of progress.
- **No-shame restart.** Missed a week? Open the project and say "I'm back." Claude shrinks the next step instead of catching up everything.
- **Public commitment (optional).** Tell a colleague or post monthly on LinkedIn what you learned. It also builds your profile for the job goal.

For procrastination beyond this project, a separate "Personal coach" project works better; see the chat for questions to set it up.
