# Claude Code Guidelines

Based on Andrej Karpathy's critiques of LLM coding habits.

## 1. Think Before Coding

Force explicit reasoning before writing any code. Surface assumptions and tradeoffs upfront. Do not start implementing until the approach is clear and agreed upon.

## 2. Simplicity First

Write the minimum code that solves the problem. Ruthlessly cut overengineered abstractions. If it doesn't need to exist, don't write it.

## 3. Surgical Changes

Only touch what's necessary. Do not "improve" adjacent code, refactor unbroken things, or expand scope beyond the task. One problem, one fix.

## 4. Goal-Driven Execution

Transform vague tasks into verifiable success criteria before starting. Example: "Fix the bug" becomes "Write a test that reproduces the bug, then make it pass." Make done mean something specific.
