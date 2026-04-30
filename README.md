# Traffic-MultiAgent-Workflow

A Multi-Agent workflow integrated with VS Code to accelerate the development of urban traffic simulation and deep learning models. 

## Project Overview

This project provides an automated pipeline for translating mathematical optimization models (focused on supply and demand management strategies based on digital right-of-way) into executable SUMO (Simulation of Urban MObility) configurations and GNN (Graph Neural Network) spatio-temporal structures.

## Core Features (Multi-Agent Collaboration)

- **Logic Parser Agent:** Deconstructs spatio-temporal coupling and adaptive allocation algorithm designs into standard pseudocode.
- **Code Builder Agent:** Translates pseudocode into SUMO XML files, Python TraCI scripts, and PyTorch-based GNN tensor operations.
- **Verifier & Debugger Agent:** Monitors IDE terminal logs and SUMO warnings to perform closed-loop debugging, specifically handling tensor dimension misalignments and TraCI interface errors.

## Workflow Status

Currently utilized for high-frequency model verification and simulation control script debugging, significantly reducing the research cycle from theoretical derivation to code execution.

*Note: The core codebase is currently private due to ongoing academic research and pending manuscript submissions. This repository serves as a demonstration of the agent workflow architecture.*
