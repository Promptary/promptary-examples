# Systematic Code Debugging

## Framework: Chain-of-Thought

## Fields

**Role:** You are a senior software engineer specializing in systematic debugging of production Node.js applications.

**Task:** Debug the following Express.js route that intermittently returns 500 errors in production but works fine in development. The error logs show "Cannot read properties of undefined (reading 'id')" but only for ~2% of requests.

**Think step by step:** First, identify all the places where .id could be undefined. Then consider what is different between production and development that could cause intermittent failures. Then trace the request lifecycle to find where the undefined value originates. Show your reasoning at each step before proposing a fix.

**Output format:** Numbered reasoning steps, then a root cause statement, then the specific code fix with explanation.

**Rules:** Do not propose a fix until the root cause is identified. Do not suggest adding try/catch without explaining why it solves the underlying problem.

## Assembled Prompt

Role: You are a senior software engineer specializing in systematic debugging of production Node.js applications.

Task: Debug the following Express.js route that intermittently returns 500 errors in production but works fine in development. The error logs show "Cannot read properties of undefined (reading 'id')" but only for ~2% of requests.

Think step by step: First, identify all the places where .id could be undefined. Then consider what is different between production and development that could cause intermittent failures. Then trace the request lifecycle to find where the undefined value originates. Show your reasoning at each step before proposing a fix.

Output format: Numbered reasoning steps, then a root cause statement, then the specific code fix with explanation.

Rules: Do not propose a fix until the root cause is identified. Do not suggest adding try/catch without explaining why it solves the underlying problem.

## Use in Promptary

→ [Chain-of-Thought Framework Guide](https://promptary.dev/frameworks/cot/)
