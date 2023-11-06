# ChatGPT Custom Instructions Library

This repository contains a curated collection of custom instructions designed
to optimize interactions with the ChatGPT model by OpenAI.

## Table of Contents
- [Introduction](#introduction)
- [What are Custom Instructions?](#what-are-custom-instructions)
- [Getting Started](#getting-started)
- [Structure of Instructions](#structure-of-instructions)
- [Repository Structure](#repository-structure)

## Introduction
ChatGPT, developed by OpenAI, enables custom instructions to tailor model
interactions. This repository offers a library of such instructions across
various scenarios.

## What are Custom Instructions?
Custom Instructions are a way to provide guidance to the ChatGPT model,
enhancing its output to better align with user expectations. By providing a
specific context or directive, users can steer the conversation in a desired
direction, making the model's response more contextually relevant. They serve
as a means to customize and refine interactions without modifying the model's
core behavior.

- [OpenAI official Custom Instructions release, blog post](https://openai.com/blog/custom-instructions-for-chatgpt)

## Getting Started

1. Clone the repository (optional):

```
git clone https://github.com/Caseraw/chatgpt-custom-instructions.git
```

2. Browse the instructions by navigating to the relevant folders and files
   In the [scenarios](#repository-structure) folder.

## Structure of Instructions
Each instruction set contains:
- **Scenario**: A brief description of when the instruction is useful.
- **Instruction**: The custom instruction text.

## Repository Structure
The repository is organized as follows:
- `/scenarios`: Root directory containing all instruction sets.
- `/topic-name`: Directories named after the scenario or topic they cover.
 - `instruction.md`: Individual markdown files detailing the custom
   instruction, scenario, and example interaction.

For example:
```
/scenarios
    /elizabethan-era
        instruction.md
    /sci-fi-dialogues
        instruction.md
```

**Note**: This repository is not officially affiliated with OpenAI. It's a
community-driven effort to enhance ChatGPT interactions.
