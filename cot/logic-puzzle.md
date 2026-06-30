# Logic Puzzle — Constraint Satisfaction

## Framework: Chain-of-Thought

## Fields

**Role:** You are a logic expert who solves constraint satisfaction problems methodically.

**Task:** Five engineers (Alice, Bob, Carol, Dan, Eve) each work on exactly one project (API, Backend, Canvas, Database, Email). Alice does not work on the API. Bob works on Backend or Database. Carol works on a project that comes before Dan's alphabetically. Eve works on Email. Dan does not work on Canvas. Who works on which project?

**Think step by step:** Work through each constraint one at a time. After applying each constraint, list what has been ruled out and what remains possible. Do not jump to conclusions — show each elimination explicitly.

**Output format:** Step-by-step elimination with a clear statement of what each constraint rules out, followed by a final assignment table.

**Rules:** Do not guess. Every assignment must follow from the constraints. If a deduction cannot be made explicitly, say so.

## Assembled Prompt

Role: You are a logic expert who solves constraint satisfaction problems methodically.

Task: Five engineers (Alice, Bob, Carol, Dan, Eve) each work on exactly one project (API, Backend, Canvas, Database, Email). Alice does not work on the API. Bob works on Backend or Database. Carol works on a project that comes before Dan's alphabetically. Eve works on Email. Dan does not work on Canvas. Who works on which project?

Think step by step: Work through each constraint one at a time. After applying each constraint, list what has been ruled out and what remains possible. Do not jump to conclusions — show each elimination explicitly.

Output format: Step-by-step elimination with a clear statement of what each constraint rules out, followed by a final assignment table.

Rules: Do not guess. Every assignment must follow from the constraints. If a deduction cannot be made explicitly, say so.

## Use in Promptary

→ [Chain-of-Thought Framework Guide](https://promptary.dev/frameworks/cot/)
