# AI_raw_French_Gourmet_Showcase

## Overview
AI Raw French Gourmet is an applied AI system designed to generate **raw, no-cook, plant-based and often nut-free recipes**, inspired by **French gastronomy**.

The project focuses on **culinary reasoning**, not just text generation, by combining:
- technical food science rules
- structured culinary knowledge
- and large language model reasoning

This repository is a **public showcase**.  
The core source code and datasets are kept private for intellectual property protection.

---

## Problem
Generic language models can generate recipes, but they:
- ignore raw food constraints (temperature, hydration, gelification)
- fail to preserve gastronomic identity
- cannot explain *why* a recipe works

This leads to recipes that are **technically incorrect**, inconsistent or unusable in practice.

---

## Solution
AI Raw French Gourmet addresses this by combining:

- **Domain-specific technical rules** (textures, hydration, emulsions)
- **Curated culinary datasets** (raw adaptations of French dishes)
- **Explainable reasoning** through structured prompts and retrieval

The system does not “invent” randomly — it reasons within culinary constraints.

---

## System Architecture
The architecture is based on a **dual RAG approach**:

- **RAG-TECHNICAL**  
  Technical knowledge base (texture engineering, raw constraints, transformations)

- **RAG-RECIPES**  
  Culinary knowledge base (raw recipes, flavor balance, gastronomic styles)

These are orchestrated by an LLM layer that:
- interprets the user request
- retrieves relevant knowledge
- generates a structured and explainable recipe

*See architecture diagram below.*

---

## Demo
**Video demonstration:** *(link to Loom or Google Drive)*

The demo shows:
- how a user enters a culinary request
- how the system retrieves domain knowledge
- how a raw recipe is generated with reasoning

---

## Features
- Raw, no-cook recipe generation
- Nut-free and allergen-aware logic
- Texture-aware formulation (creamy, firm, aerated, etc.)
- Culinary explainability (why ingredients and steps are chosen)
- Modular architecture ready for extension (nutrition, personalization)

---

## Tech Stack
- Python
- Retrieval-Augmented Generation (RAG)
- Vector embeddings
- LLM orchestration (Gemini / compatible models)
- FastAPI (backend services)
- Lightweight demo interface

---

## Project Status
- Core system: functional (private repository)
- Public showcase: documentation & demo
- Ongoing research and refinement

---

## Roadmap
- Enhanced nutritional reasoning
- Personalization based on user constraints
- Productization and monetization (2026)

---

## About
This project was developed as part of an applied AI bootcamp and personal research into **AI-driven culinary systems**.

For collaboration, research or professional inquiries, feel free to connect via GitHub or LinkedIn.
