---
layout: page
title: Battery Electric Bus Charging Optimization
description: This study develops a (MILP) model for scheduling the charging of battery electric buses (BEBs) operating from a single depot. The model incorporates battery-energy dynamics, bus and charger availability, a SoC-dependent charging power with a Time-of-Use (ToU) tariff.
img: assets/img/plot_soc_tou_uv.png
importance: 1
related_publications: false
---

## Overview

This research develops a **Mixed-Integer Linear Programming (MILP)** framework for optimizing the charging schedule of Battery Electric Bus (BEB) fleets with **SoC-dependent charging power**.

The model determines when and at what power level each bus should charge while considering realistic operational and infrastructure constraints.

## Research Focus

The framework incorporates:

- State-of-Charge-dependent charging power
- Time-of-Use electricity pricing
- Charger availability
- Depot power capacity
- Vehicle operating schedules
- Charging-session continuity
- Battery energy dynamics

## Methodology

The optimization model is implemented in **Python** and solved using **Gurobi Optimizer**.

**Methods:** Operations Research · MILP · Scheduling · Mathematical Programming · Sensitivity Analysis

## Code

[View GitHub Repository](https://github.com/jlab-eng/bus-charging-optimization)
