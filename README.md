# Navinator

### Navigate Any Codebase. Understand How It Works.

[![Python](https://img.shields.io/badge/Python-3.11+-3776ab?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-18+-61dafb?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178c6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Anthropic](https://img.shields.io/badge/Anthropic-Claude-191919?logo=anthropic&logoColor=white)](https://www.anthropic.com/)
[![xAI](https://img.shields.io/badge/xAI-Grok-000000?logo=x&logoColor=white)](https://x.ai/)
[![NetworkX](https://img.shields.io/badge/NetworkX-Graph%20Analysis-e76f51)](https://networkx.org/)

<p align="center">
  <img src="readme_Images/navinator.png" width="90%" alt="Navinator">
</p>

## Overview

Navinator is an AI-powered codebase navigator that helps developers understand unfamiliar Python backends.

Instead of giving you another AI-generated explanation, Navinator **walks through the actual code**.

Ask a question like:

> How does login work, and where does the request end up?

Navinator finds the relevant functions, follows real call and dependency relationships, and turns them into a guided tour through the code.

Each stop shows the actual function source, file, and line that led to the next step.

### Project Links

- [Demo Website](https://navinator.vercel.app/)
- [GitHub Repository](https://github.com/AadityaK16/codebase-navigator)

## The Problem

Understanding an unfamiliar codebase is difficult.

Modern repositories can contain thousands of files, functions, imports, and dependencies. Developers joining a project often have to:

- Search through dozens of files
- Trace function calls manually
- Figure out how requests move through the backend
- Reconstruct relationships between modules
- Read outdated or incomplete documentation

Traditional AI coding assistants can explain individual pieces of code, but they don't always show **how those pieces connect**.

## Our Solution

Navinator combines **code parsing, graph analysis, and AI-powered navigation** to create a map of the codebase.

```text
Question
   ↓
Relevant Code
   ↓
Graph Search
   ↓
Validated Call Path
   ↓
Guided Code Tour
