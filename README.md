# Evaluation and Benchmarking of LLM Agents

## CMPE 255 - Short Story Assignment

This repository contains my Short Story Assignment for CMPE 255.

The topic is based on the research paper **"Evaluation and Benchmarking of LLM Agents: A Survey"** by Mohammadi et al. (KDD 2025).

The goal of this project is to understand how LLM-based agents are evaluated, what makes an agent reliable, and why successfully completing a task does not always mean that the agent has performed well.

## Original Research Paper

**Title:** Evaluation and Benchmarking of LLM Agents: A Survey

**Authors:** Mohammadi et al.

**Conference:** KDD 2025

**Paper:** https://arxiv.org/abs/2507.21504

The paper provides an overview of existing methods for evaluating LLM agents. It organizes evaluation into two main areas:

- **Evaluation Objectives:** What should be evaluated, including agent behavior, capabilities, reliability, and safety.
- **Evaluation Process:** How agents are evaluated, including benchmarks, evaluation methods, metrics, and testing environments.

## Project Overview

In this project, I summarize the main ideas from the survey and discuss several important questions about evaluating autonomous agents.

The main topics include:

- How LLM agents work and interact with tools.
- Common evaluation metrics and benchmarks.
- The difference between task completion and task quality.
- How unclear user instructions can affect agent behavior.
- The balance between agent autonomy and user control.
- Why agent capabilities should not be confused with user authorization.

I also discuss an example from my previous autonomous agent research involving a shopping task. This example shows how an agent may make progress toward completing a request without fully understanding the user's personal preferences.

## My Perspective

One of my main takeaways is that **task completion alone is not enough to determine whether an agent is reliable or helpful**.

An agent may successfully perform the requested actions but still fail to satisfy the user's actual needs.

I also believe that user instructions play an important role in agent performance. When instructions are unclear, an agent may make assumptions that do not match what the user intended. However, allowing agents to make too many decisions independently may also introduce safety and authorization risks.

In my view, a reliable agent should try to complete tasks effectively while respecting user intentions, permissions, and safety boundaries. When an important decision requires user approval, the agent should ask rather than make that decision on its own.

## Project Materials

### Medium Article

The article explains the main ideas from the survey and includes my own discussion of task completion, prompt ambiguity, and agent autonomy.

**Article Link:** [Read the Medium Article](https://medium.com/@yhz1805/beyond-task-success-what-makes-an-llm-agent-truly-reliable-b64f5fa51e3a)

### SlideShare Presentation

The presentation summarizes the main concepts and key takeaways from the article.

**SlideShare Link:** [View the Presentation](https://docs.google.com/presentation/d/1J3yhusPkcgd9pAGO1j_kZ07lVeQgsavz/edit?usp=sharing&ouid=118365490186443634549&rtpof=true&sd=true)

**PowerPoint File:** [Download the PPT](LLM_Agent_Presentation.pptx)

### Presentation Video

This video provides a walkthrough of the research paper, evaluation methods, and my personal analysis.

**Video Link:** [Watch the Presentation](PASTE_VIDEO_LINK_HERE)

## Conclusion

Evaluating LLM agents requires more than checking whether they complete tasks.

A good evaluation should also consider how agents make decisions, whether their actions match user needs, and whether they operate within appropriate safety and authorization boundaries.

As autonomous agents become more capable, these factors will become increasingly important for real-world applications.

## References

Mohammadi et al. (2025). *Evaluation and Benchmarking of LLM Agents: A Survey*. KDD 2025. https://arxiv.org/abs/2507.21504

Other related research discussed in the article includes WebArena, τ-bench, and AgentDojo.
