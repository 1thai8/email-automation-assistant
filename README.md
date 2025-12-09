# Email Automation — Prompt Engineering Project

## Overview
This project contains prompt engineering work focused on automating email tasks such as:
- summarization
- reply drafting
- triage
- tone adaptation
- word-limit-bounded generation

It demonstrates iterative improvement (v1 → v2 → v3) and provides real model outputs for recruiters.

## Structure
- prompts/ — prompt versions (v1, v2, v3)
- tests/ — test cases used to evaluate prompts
- examples/ — model outputs for each prompt version

## How to Evaluate Locally
1. Open any LLM playground.
2. Paste the prompt from prompts/prompt_v1.md.
3. Insert the test cases from tests/test-cases.json.
4. Save the generated output in examples/.
