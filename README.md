# The AI Agents Class
<img style="widTue:600px; height:auto;" alt="Gemini_Generated_Image_l33ud6l33ud6l33u" src="https://github.com/user-attachments/assets/417c3619-5a52-445a-9007-4d9fc155e3d6" />

This is the website for the *AI agents* class (CS 839, Spring 2026) at UW-Madison.

For submitting assignments, reports, reviews, etc., see canvas.

See [course info](course-info.md) for class structure, presentation advice, and compute resources.

## schedule

### week 0 (Jan 20)

*We begin by providing a class overview and a deep dive into how to build LLM-based AI agents using a variety of techniques and frameworks*

Tue: Class overview

Thu: Building agents

### week 1 (Jan 27)

*We will start by covering "classic" papers that took LLMs from next-word-prediction machines to programs that can reason and act.*

Tue:
- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
    - *supplementary:* [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171)
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)
  - *supplementary:* [Kimi K2: Open Agentic Intelligence](https://arxiv.org/abs/2507.20534)
- *supplementary:* [The Llama 3 Herd of Models](https://arxiv.org/abs/2407.21783)
- *supplementary:* [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)

Thu:
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)
  - *supplementary:* [Large Language Models as Tool Makers](https://arxiv.org/abs/2305.17126)
  - *supplementary* [ART: Automatic multi-step reasoning and tool-use for large language models
](https://arxiv.org/abs/2303.09014)
- [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)
  - *supplementary* [Graph of Thoughts: Solving Elaborate Problems with Large Language Models
](https://ojs.aaai.org/index.php/AAAI/article/view/29720)

see also [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents)

### week 2 (Feb 3)

*This week, we will talk about coding (or software engineering) agents and benchmarks, which has so far been the most successful application of AI agents*

Tue:
- [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)
  - *supplementary* [Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces](https://openreview.net/forum?id=a7Qa4CcHak)
- [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793)
  - *supplementary:* [Agentless: Demystifying LLM-based Software Engineering Agents](https://arxiv.org/abs/2407.01489)

Thu:
- [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741)
  - *supplementary:* [RepairAgent: An Autonomous, LLM-Based Agent for Program Repair](https://arxiv.org/abs/2403.17134)
- [BaxBench: Can LLMs Generate Correct and Secure Backends?](https://arxiv.org/pdf/2502.11844)
  - *supplementary:* [RedCode: Risky Code Execution and Generation Benchmark for Code Agents](https://arxiv.org/abs/2411.07781)
  - *supplementary:* [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://arxiv.org/abs/2307.13854)

### week 3 (Feb 10)
*This week, we will cover "deep research" agents, which are agents that generate comprehensive reports on a topic.*

Tue:
- [Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models](https://arxiv.org/abs/2402.14207)
- [Agent Laboratory: Using LLM Agents as Research Assistants](https://arxiv.org/abs/2501.04227)
- *supplementary:* [ResearchAgent: Iterative Research Idea Generation over Scientific Literature](https://arxiv.org/abs/2404.07738)
- *supplementary:* [Deep research agents:
A systematic examination and roadmap](https://arxiv.org/pdf/2506.18096)
- *supplementary:* [How we built our multi-agent research system](https://www.anthropic.com/engineering/multi-agent-research-system)

Thu:
- [PaperQA: Retrieval-Augmented Generative Agent for Scientific Research](https://arxiv.org/abs/2312.07559)
- [LiveResearchBench: A Live Benchmark for User-Centric Deep Research in the Wild](https://arxiv.org/abs/2510.14240)
- *supplementary:* [Can LLMs Generate Novel Research Ideas?](https://arxiv.org/abs/2409.04109)
- *supplementary:* [DR Tulu: Reinforcement Learning with Evolving Rubrics for Deep Research](https://arxiv.org/pdf/2511.19399)

### week 4 (Feb 17)

*We will now switch attention to agents whose goal is to automate or augment the scientific process.*

Tue:
- [The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/abs/2408.06292)
- [Autonomous Chemical Research with Large Language Models](https://www.nature.com/articles/s41586-023-06792-0)
  - *supplementary:* [ChemCrow: Augmenting Large Language Models with Chemistry Tools](https://arxiv.org/abs/2304.05376)
  
Thu:
- [Towards an AI Co-Scientist](https://arxiv.org/abs/2502.18864)
  - *supplementary:* [SciAgents: Automating Scientific Discovery through Multi-Agent Systems](https://arxiv.org/abs/2409.05556)
- [Automated Hypothesis Validation with Agentic Sequential Falsifications](https://arxiv.org/abs/2502.09858)

### week 5 (Feb 24)

*AI agents, by virtue of their transformer architecture, mix instructions and data, creating a huge security risk. The following papers study this issue*

Tue:
- [Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)
- [AgentDojo: A Dynamic Environment to Evaluate Attacks and Defenses for LLM Agents](https://arxiv.org/abs/2406.13352)
- *supplementary:* [Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/abs/2307.02483)

Thu:

- [CaMeL: Defeating Prompt Injections by Design](https://arxiv.org/abs/2503.18813)
  - *supplementary:* [The lethal trifecta for AI agents: private data, untrusted content, and external communication](https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/)
  - *supplementary:* https://ai.meta.com/blog/practical-ai-agent-security/
- [ceLLMate: Sandboxing Browser AI Agents](https://arxiv.org/abs/2512.12594)


### week 6 (Mar 3)

*Over the next two weeks, we will cover a range of ideas for optimizing and improving agents.*

Tue:
- [DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines](https://arxiv.org/abs/2310.03714)
  - see DSPy codebase as well
- [TextGrad: Automatic Differentiation via Text](https://arxiv.org/abs/2406.07496)
- *supplementary:* [Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409)

Thu:
- [Automated Design of Agentic Systems](https://arxiv.org/abs/2408.08435)
- [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457)
- *supplementary:* [EvoPrompt: Connecting LLMs with Evolutionary Algorithms Yields Powerful Prompt Optimizers](https://arxiv.org/abs/2309.08532)
- *supplementary*: [Trace is the New AutoDiff: Unlocking Efficient Optimization of Computational Workflows](https://arxiv.org/abs/2406.16218)


### week 7 (Mar 10)

Tue:
- [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291)
- [Gödel Agent: A Self-Referential Agent Framework for Recursive Self-Improvement](https://arxiv.org/abs/2410.04444)
  
Thu:
- [AlphaEvolve: A Gemini-powered Coding Agent for Designing Advanced Algorithms](https://deepmind.google/discover/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/)
- [Live-SWE-agent: Can Software Engineering Agents Self-Evolve on the Fly?](https://arxiv.org/abs/2511.13646)
  - *supplementary:* [Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models](https://arxiv.org/abs/2310.04406)

### week 8 (Mar 17)

*We will continue the discussion of agents that search the space of possible solutions.*

Tue:
- [Competition-Level Code Generation with AlphaCode](https://arxiv.org/abs/2203.07814)
- [Solving olympiad geometry without human demonstrations (AlphaGeometry)](https://www.nature.com/articles/s41586-023-06747-5)
  - *supplementary:* [Olympiad-level formal mathematical reasoning with reinforcement learning (AlphaProof)](https://www.nature.com/articles/s41586-025-09833-y)
  - *supplementary:* [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm (AlphaZero)](https://arxiv.org/abs/1712.01815)

Thu:
- [ShinkaEvolve: Towards Open-Ended And Sample-Efficient Program Evolution](https://arxiv.org/abs/2509.19349)
  - *supplementary:* [Digital Red Queen: Adversarial Program Evolution in Core War with LLMs](https://arxiv.org/abs/2601.03335)
- [Evolution through Large Models](https://arxiv.org/abs/2206.08896)
  - *supplementary:* [Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution](https://arxiv.org/abs/2309.16797)


### week 9 (Mar 24)
*We now switch attention to multi-agent systems.*

Tue:
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)
- [CAMEL: Communicative Agents for "Mind" Exploration of Large Language Models](https://arxiv.org/abs/2303.17760)
- *supplementary:* [Improving Factuality and Reasoning in Language Models through Multiagent Debate](https://arxiv.org/abs/2305.14325)

Thu:
- [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155)
  - *supplementary:* [Don't sleep on single agent systems](https://openhands.dev/blog/dont-sleep-on-single-agent-systems)
  - *supplementary:* [Prompt Infection: LLM-to-LLM Prompt Injection within Multi-Agent Systems](https://arxiv.org/abs/2410.07283)
- [Towards a Science of Scaling Agent Systems](https://arxiv.org/abs/2512.08296)
  - *supplementary:* [MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352)
  - *supplementary:* [AgentVerse: Facilitating Multi-Agent Collaboration](https://arxiv.org/abs/2308.10848)

### 🌴 Spring Break (Mar 28 - Apr 5)

### week 10 (Apr 7)

This week, we will see how agents can use memory to improve their performance and explore some other topics.

Tue:
- [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560)
- [Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427)
- *supplementary:* [Think-in-Memory: Recalling and Post-thinking Enable LLMs with Long-Term Memory](https://arxiv.org/abs/2311.08719)
- *supplementary:* [A-Mem: Agentic Memory for LLM Agents](https://arxiv.org/pdf/2502.12110)
- *supplementary:* [Recursive language models](https://arxiv.org/abs/2512.24601)

Thu:
- [Mixture-of-Agents Enhances Large Language Model Capabilities](https://arxiv.org/abs/2406.04692)
  - *supplementary:* [More Agents Is All You Need](https://arxiv.org/pdf/2402.05120)
- [Scaling Long-Horizon LLM Agent via Context-Folding](https://arxiv.org/pdf/2510.11967)
  - *supplementary:* [Measuring AI Ability to Complete Long Tasks](https://arxiv.org/pdf/2503.14499)

### week 11 (Apr 14)

*Work on project week*

### week 12 (Apr 21)

*Project presentation week*


### week 13 (Apr 28)

*Project presentation week*

## assignments

- [Build a Coding Agent](assignment.md) — individual assignment

## grading
- 15% buy-in assignment
- 15% participation
- 10% presentation
- 10% paper reviews
- 50% final project (write up and presentation)
