# Irace Tool Rerun Findings

This document details the rerun of our findings for two configurations using the Irace tool. We are optimizing the parameters for the Minisat benchmarks.

## Configuration Setup

Four target runners have been established with the following specifications:

1. Measure: Time, Retry: 1
2. Measure: Time, Retry: 2
3. Measure: Performance Cycles, Retry: 1
4. Measure: Performance Cycles, Retry: 2

## Findings

A comparison between the results of Time with Retry = 1 and Cycles with Retry = 2 reveals significant differences:

- The run utilizing Performance Cycles as a measure completed in just **1 hour and 15 minutes**, compared to **1 hour and 46 minutes** for the Time measure.
- The configuration that used Performance Cycles was found to be **26.34% more time efficient** than the one using Time.

These findings suggest that optimizing for Performance Cycles not only enhances the speed of the process but also improves the overall time efficiency of the configuration.
