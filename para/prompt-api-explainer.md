# Technical Explainer — Prompt API Endpoints

## Framework: PARA

## Fields

**Problem:** Developers hardcode AI prompts directly into their application code. When the prompt needs updating — a wording tweak, a tone change, a new constraint — it requires a code change, a PR, and a redeployment. For teams iterating on prompts daily, this is a significant operational bottleneck.

**Approach:** Explain how serving prompts from a stable REST API endpoint decouples prompt management from application code. Cover: what the endpoint looks like, how the application calls it at runtime, and what happens when the prompt is updated.

**Result:** A 600-word technical explainer in markdown, suitable for a developer blog. One curl example. One JavaScript fetch example. A before/after comparison showing the hardcoded approach vs the API approach.

**Application:** Backend developers at companies with 5–50 engineers who are actively shipping AI features and starting to feel the pain of managing prompts in code. They understand REST APIs and are comfortable with curl. They are not yet aware that prompt-as-API is a pattern.

**Rules:** Do not explain what REST is. Start with the problem scenario, not with "In this article". The before/after comparison must show real code, not pseudocode. End with a specific next step the reader can take today.

## Assembled Prompt

Problem: Developers hardcode AI prompts directly into their application code. When the prompt needs updating — a wording tweak, a tone change, a new constraint — it requires a code change, a PR, and a redeployment. For teams iterating on prompts daily, this is a significant operational bottleneck.

Approach: Explain how serving prompts from a stable REST API endpoint decouples prompt management from application code. Cover: what the endpoint looks like, how the application calls it at runtime, and what happens when the prompt is updated.

Result: A 600-word technical explainer in markdown, suitable for a developer blog. One curl example. One JavaScript fetch example. A before/after comparison showing the hardcoded approach vs the API approach.

Application: Backend developers at companies with 5–50 engineers who are actively shipping AI features and starting to feel the pain of managing prompts in code. They understand REST APIs and are comfortable with curl. They are not yet aware that prompt-as-API is a pattern.

Rules: Do not explain what REST is. Start with the problem scenario, not with "In this article". The before/after comparison must show real code, not pseudocode. End with a specific next step the reader can take today.

## Use in Promptary

→ [PARA Framework Guide](https://promptary.dev/frameworks/para/)
