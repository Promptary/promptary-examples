# Git Commit Type Classification

## Framework: Few-Shot

## Fields

**Task:** Classify each git commit message into its Conventional Commits type: feat, fix, docs, refactor, test, chore, or perf.

**Example 1:** Input: "add REST API endpoint for fetching prompts by ID"
Output: feat

**Example 2 (optional):** Input: "correct wrong HTTP status code returned on auth failure"
Output: fix

**Example 3 (optional):** Input: "update README with n8n integration example"
Output: docs

**Output format:** Return only the type label in lowercase. No colon, no scope, no explanation.

**Rules:** Use only the seven types listed. If a commit is ambiguous between feat and refactor, choose feat if it adds new user-visible behavior, refactor if it does not.

## Assembled Prompt

Task: Classify each git commit message into its Conventional Commits type: feat, fix, docs, refactor, test, chore, or perf.

Example 1: Input: "add REST API endpoint for fetching prompts by ID"
Output: feat

Example 2 (optional): Input: "correct wrong HTTP status code returned on auth failure"
Output: fix

Example 3 (optional): Input: "update README with n8n integration example"
Output: docs

Output format: Return only the type label in lowercase. No colon, no scope, no explanation.

Rules: Use only the seven types listed. If a commit is ambiguous between feat and refactor, choose feat if it adds new user-visible behavior, refactor if it does not.

## Use in Promptary

→ [Few-Shot Framework Guide](https://promptary.dev/frameworks/fewshot/)
