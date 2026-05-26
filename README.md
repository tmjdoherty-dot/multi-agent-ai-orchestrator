# AI Orchestra

A visual, node-based multi-agent AI orchestration tool — built as a single HTML file.

## What it does

AI Orchestra lets you design custom AI pipelines using a drag-and-drop canvas. 
You can route prompts through multiple AI models simultaneously, collect and 
synthesise their outputs, and chain the results into further reasoning steps — 
all without writing code.

## Key Features

- **Visual canvas** — build pipelines using Model, Prompt, Collect, and Output nodes
- **Multi-model routing** — send the same prompt to multiple AI models in parallel
- **Collect nodes** — aggregate responses from multiple models into a single output
- **Loop support** — repeat entire pipelines a defined number of times
- **Delegation mode** — one AI breaks a task into subtasks and distributes them 
  to other models automatically
- **Chat interface** — interact with any configured model directly
- **Obsidian integration** — reference notes using [[filename]] syntax to inject 
  file contents as context
- **System prompts** — assign individual system prompts per node
- **Multi-provider support** — works with OpenAI, Anthropic (Claude), and 
  OpenRouter via API keys added in settings

## How to use

1. Open `orchestra.html` in any modern browser
2. Go to **Settings** and add your API keys for your chosen providers
3. Open the **Models** canvas and build your pipeline using node blocks
4. Connect nodes: Prompt → Models → Collect → Output
5. Switch to the **Chat** tab to run your pipeline

## Why I built this

I wanted a tool that treated multiple AI models as a single, customisable 
reasoning system — routing tasks intelligently rather than relying on one model 
for everything. Built entirely as a self-contained HTML file for maximum 
portability.

## Tech

Single-file HTML/CSS/JavaScript. No dependencies, no build step, no server. 
Just open it.
