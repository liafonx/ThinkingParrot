# <img src="./LOGO.png" alt="Thinking Parrot Logo" width="28" style="vertical-align: middle; margin-right: 8px;" /> Thinking Parrot

An AI-assisted, concept-first approach to mastering English. This project promotes a new way to learn that goes beyond grammar drills and vocabulary lists, focusing instead on the concepts and patterns native speakers use unconsciously.

## Why this approach

This method aims to answer three practical questions for learners (especially native Chinese speakers):

- Why is there a persistent bottleneck and what blind spots do learners overlook when studying English as a second language?
- Why can you understand every word in a sentence but still miss the meaning? The “comprehension challenge” is real and different from Chinese.
- What does it mean to think in English and write authentic English? Like cooking, you must know the ingredients and a reliable recipe before you can create.

## How it works

The approach is holistic, multi-layered and 360°:

- We promote creative learning, not rote learning.
- We adopt a reverse-engineering mindset: take language apart, then reassemble to build your own style.
- We help you “learn to look”, “learn to think”, and “learn to play” with English through new concepts.

You will quickly raise awareness, simplify the complex, and gain a durable mental model of English usage.

## Pillars & Principles

![Pillars and Principles](./Pillars-and-Principles.png)

The visual above summarizes the 6 Pillars and 7 Principles that structure this learning method. The pillars capture the major dimensions of English usage (such as function vs. content or literal vs. figurative), while the principles highlight actionable tendencies native speakers rely on (such as variety, intensification, ellipsis). Use the diagram as a quick reference: identify which pillar a sentence operates on, then apply the relevant principles to generate or refine your expression.

## Architecture

This repository contains the learning methodology and reference materials. The complete system follows a client-server architecture with two main components:

**Frontend** - WeChat Mini Program built with JavaScript/WXML/WXSS  
[ThinkingParrot-Miniprogram](https://github.com/liafonx/ThinkingParrot-Miniprogram.git)

**Backend** - Django-based Python API service handling conversational AI and learning assessments  
[ThinkingParrot-Backend](https://github.com/liafonx/ThinkingParrot-Backend.git)

The Mini Program communicates with the backend through RESTful APIs, sending user interactions and receiving structured responses (lessons, feedback, assessments). This modular design allows independent development and deployment of the user interface and core learning engine.

## Materials

- Poster overview: `Language Chatbot 3.0 Poster.pdf` (high-level introduction to the method, pillars, and principles)
