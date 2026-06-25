# CPU Scheduling Simulator

A clean, browser-based CPU scheduling simulator for comparing classic operating system algorithms side by side.

**Live Demo:** https://aritradev.github.io/CPU-Scheduling-Simulator/

 [![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=aritradev.CPU-Scheduling-Simulator)](https://aritradev.github.io/CPU-Scheduling-Simulator/)

## Overview

This project helps students, educators, and OS enthusiasts visualize how different CPU scheduling strategies behave with the same input set. It simulates and compares:

- FCFS (First Come First Serve)
- SJF (Shortest Job First)
- SRTF (Shortest Remaining Time First)
- Round Robin

The interface lets you enter processes, choose a scheduling goal, and instantly view Gantt charts, turnaround time, waiting time, and algorithm recommendations.

## What It Solves

CPU scheduling is one of the most important concepts in operating systems, but it is often hard to understand from theory alone. This simulator solves that problem by turning abstract scheduling rules into visual, measurable results.

It helps you:

- Understand how each scheduling algorithm makes decisions
- Compare preemptive and non-preemptive scheduling behavior
- See waiting time and turnaround time differences instantly
- Visualize process execution with a Gantt chart
- Test different process arrival and burst time combinations without manual calculation
- Choose the most suitable algorithm based on the selected optimization goal

In short, this project removes the need to calculate scheduling outcomes by hand and makes algorithm behavior easy to observe.

## Key Features

- Interactive process input table
- Support for custom arrival and burst times
- Preemptive SRTF scheduling
- Round Robin time quantum support
- Visual Gantt chart output for every algorithm
- Per-process metrics including completion, turnaround, and waiting time
- Average waiting time and turnaround time comparison
- Recommendation panel based on the selected goal
- Fully client-side execution in the browser

## Algorithms Included

| Algorithm | Type | Behavior |
| --- | --- | --- |
| FCFS | Non-preemptive | Runs processes in arrival order |
| SJF | Non-preemptive | Picks the shortest available job |
| SRTF | Preemptive | Always runs the job with the shortest remaining time |
| Round Robin | Preemptive | Rotates processes using a fixed time quantum |


## How To Use

1. Open the live demo or run the HTML file locally in a browser.
2. Enter one or more processes with arrival time and burst time.
3. Select the optimization goal and Round Robin quantum if needed.
4. Click Run Simulation.
5. Review the charts, metrics, and recommended algorithm.

## Ideal For

- Operating systems coursework
- Classroom demonstrations
- Self-study and exam preparation
- Quick comparison of scheduling strategies

## Project Strengths

- Simple and fast to use
- No backend required
- Easy to host on GitHub Pages
- Strong visual explanation of scheduling behavior

## Notes

If you want SRTF to show a visibly different result from SJF, use input sets where a shorter process arrives while a longer process is already running. That is the scenario where preemption becomes visible.
