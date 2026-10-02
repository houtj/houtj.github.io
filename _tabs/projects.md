---
# the default layout is 'page'
title: Research Projects
icon: fas fa-laptop-code
order: 2
---

<!-- Showcase your projects here. -->
---
I'm leading research on **time series analysis** at the AI Lab.

I believe a time series foundation model relying on numbers alone can't be trusted in industry settings. To be trustworthy, it needs to take language as context and instruction, and to justify its outputs in language the user can reason about.

For example, no one would buy or sell a stock simply because a model predicted a price move from historical numbers alone — people want to know *why* before acting on it.

This is why my research centers on **language-guided time series analysis**, combining the pattern-recognition strength of time series models with the contextual reasoning and explainability of language.

---

## Agentic time series analysis

We work on agentic systems for time series analysis, with the goal of adapting time series analysis to domain-specific context.

Our flagship contribution is an event logic tree built on Allen's interval algebra, which mitigates hallucination and enables reliable agent orchestration for time series pattern discovery.

---

## Language-guided time series event detection
We train models to align natural-language descriptions with time series data, making temporal patterns recognizable and searchable through language.

Our flagship contribution is GroundingMoment, which enables fast, domain-agnostic langauge-guided event detection from time series.

---

## Time series reasoning
We explore how language models can reason directly over time series, treating temporal data as a first-class modality rather than as an external tool or textual summary. The aim is to build models that can interpret evolving signals in context, explain their conclusions, and support decisions or actions.

For industrial applications, this reasoning must also be fast enough for real-time analysis. We therefore focus on compact models that retain strong reasoning capabilities while meeting the latency and efficiency requirements of operational time series workflows.

Research directions includes time series language model (TSLM) and time series-langauge-action model (TSLA).

---

## Time-series data annotation