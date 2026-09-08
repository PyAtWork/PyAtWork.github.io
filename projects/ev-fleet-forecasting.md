---
title: EV Fleet Charging Forecasting for Energy Trading
description: A forecasting API for electric vehicle fleet charging behavior, built to inform participation in intra-day energy trading.
published: false
---

## Context

Before this project, there was no forecasting approach for the charging behavior of BMW Group's electric vehicle fleet — meaning the fleet's flexibility couldn't be systematically factored into energy trading decisions.

## Approach

Using NeuralProphet, the fleet's charging behavior for a single market is forecast and served via a prediction API. The forecasted behavior is used as an input signal for participation in intra-day energy trading.

## Status

Live prediction API in production for one market.

**Stack:** Python, NeuralProphet
