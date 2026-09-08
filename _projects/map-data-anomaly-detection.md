---
title: Anomaly Detection for Worldwide Map-Data Releases
description: Introducing anomaly detection into a release process that previously had none, with results synthesized into executive reports by an LLM.
published: false
---

## Context

BMW Group's worldwide map-data release process had no systematic anomaly detection before this project — quality issues surfaced late, if at all, and reporting was manual.

## Approach

An ensemble of statistical methods generates anomaly scores and patterns across markets and map products. Rather than leaving these scores as raw output for specialists to interpret, a tightly-prompted LLM synthesizes them into executive reports — making the signal accessible to non-technical stakeholders without losing the underlying statistical rigor.

## Status

In production, integrated into the release pipeline.

**Stack:** Python, AWS (S3, DynamoDB, Athena), LLM-based report synthesis
