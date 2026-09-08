---
title: Multi-Agent Location Assistant (MVP)
description: An MVP resolving free-text customer queries into next-destination suggestions via a multi-agent system built with LangChain.
published: false
---

## Context

Customers often describe what they want in free text rather than structured search terms. The goal: turn a loosely-phrased request into an actionable next-destination suggestion.

## Approach

A multi-agent system, built with LangChain and Claude (Haiku & Sonnet), resolves free-text queries against a geospatial points-of-interest database accessed via a REST API. The project was explicitly scoped as an MVP to validate feasibility and result quality before any production investment.

## Outcome

Feasibility and result quality were validated. Insights from the evaluation were fed back to the database team to optimize data structures for this style of LLM-based query.

**Stack:** LangChain, Claude (Haiku & Sonnet), REST API integration
