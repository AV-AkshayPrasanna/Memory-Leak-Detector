# Memory Leak Detector

A browser-based simulation built as a team of three for the **Operating Systems (21CSC202J) mini-project** at SRM Institute of Science and Technology (SRMIST).

## Overview

Memory Leak Detector demonstrates the basic idea of tracking allocated memory that has not been released. Users can simulate memory allocation and deallocation, inspect allocation history, and run a detection step that flags still-active blocks as **potential memory leaks**.

> **Scope:** This is an educational browser-based simulation. It does not inspect real operating-system processes or detect memory leaks in running applications.

## Features

- Simulate allocation and deallocation using a block/variable name and size in KB
- View allocation and deallocation counts
- Track active block count and total active simulated memory
- Review allocation history, allocation/release timestamps, and block status
- Run leak detection to flag blocks that remain allocated
- Load a demo scenario and reset the simulated state
- Responsive dashboard with an olive-green and navy theme

## Built With

- HTML
- CSS
- JavaScript

## Run Locally

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.

No dependencies, package installation, or build step are required.

## How to Try the Demo

1. Enter a block name such as `bufferA`.
2. Enter a size in KB, such as `150`.
3. Choose **Allocate** and click **Apply Operation**.
4. Repeat with another block. Deallocate one block and leave another active.
5. Click **Detect Memory Leaks** to view the unreleased allocation(s).
6. Use **Reset** to clear the simulation.

## Project Team

- **M. Dev Aryan** — Frontend & UI Development
- **S. Kaushik** — Logic & Integration
- **A.V. AkshayPrasanna** — Testing & Presentation

## Academic Context

Operating Systems mini-project, course **21CSC202J**, SRM Institute of Science and Technology (SRMIST).

---

Built for learning and demonstrating memory-management concepts through an interactive simulation.
