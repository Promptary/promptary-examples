# Promptary Examples

**50+ production-ready AI prompt examples** organized by framework — ready to copy, adapt, and save to [Promptary](https://promptary.dev) for use via REST API.

Every example in this repo was built using one of the 13 prompt engineering frameworks supported by [Promptary](https://promptary.dev). Each prompt can be saved to Promptary and called from any application via a stable GET endpoint — no hardcoding, no redeployment when you update the wording.

```
GET https://promptary.dev/api/v1/prompts/:id
Authorization: Bearer pk_live_YOUR_KEY
```

---

## What is Promptary?

[Promptary](https://promptary.dev) is a prompt engineering workspace where you write structured AI prompts using 13 proven frameworks, organize them on a physics-driven canvas, and serve them to any app via a stable REST API.

- **Free forever** on the Personal plan — unlimited prompts, all 13 frameworks, full canvas
- **Developer plan** (€9/month) — unlocks the REST API endpoint for every prompt
- **Team plan** (€125/month, 5 seats) — shared workspace, prompt version history, 10 API keys

→ [Start free at promptary.dev](https://promptary.dev/register)

---

## Frameworks

| Framework | Fields | Best for | Examples |
|---|---|---|---|
| [RACE](./race/) | Role, Action, Context, Expectation | General-purpose, everyday tasks | 5 examples |
| [RISEN](./risen/) | Role, Instructions, Steps, End Goal, Narrowing | Complex multi-step tasks | 4 examples |
| [CO-STAR](./costar/) | Context, Objective, Style, Tone, Audience, Response | Content writing, communications | 4 examples |
| [RTF](./rtf/) | Role, Task, Format | Quick structured prompts | 4 examples |
| [APE](./ape/) | Action, Purpose, Expectation | Goal-aligned outputs | 4 examples |
| [CRIT](./crit/) | Context, Role, Interview, Task | Advisory, open-ended tasks | 4 examples |
| [CRAFT](./craft/) | Context, Role, Action, Format, Tone | Branded content, tone-sensitive tasks | 4 examples |
| [TAG](./tag/) | Task, Action, Goal | Outcome-driven tasks | 4 examples |
| [CARE](./care/) | Context, Action, Result, Example | Example-driven output matching | 4 examples |
| [ReAct](./react/) | Role, Instructions, Tools, Reasoning, Action, Observation | AI agents with tool use | 3 examples |
| [Image Gen](./image-gen/) | Subject, Style, Lighting, Composition, Mood, Negative, Parameters | Midjourney, DALL·E, Flux, Stable Diffusion | 4 examples |
| [Video Gen](./video-gen/) | Scene, Motion, Camera, Lighting, Style, Duration, Negative, Parameters | Sora, Runway, Pika, Kling | 3 examples |
| [Freeform](./freeform/) | Text | Existing prompts, system prompts, agent instructions | 3 examples |

---

## How to use these examples

### Option 1 — Copy and paste directly into ChatGPT, Claude, or Gemini
Each example includes the assembled prompt text at the bottom. Copy it and use it immediately.

### Option 2 — Save to Promptary and call via REST API
1. Sign up free at [promptary.dev](https://promptary.dev/register)
2. Create a new prompt using the matching framework
3. Fill in the fields from the example
4. Copy the prompt ID from the editor
5. Call it from your app:

```bash
curl https://promptary.dev/api/v1/prompts/YOUR_PROMPT_ID \
  -H "Authorization: Bearer pk_live_YOUR_KEY"
```

```javascript
const res = await fetch('https://promptary.dev/api/v1/prompts/YOUR_PROMPT_ID', {
  headers: { 'Authorization': 'Bearer pk_live_YOUR_KEY' }
});
const { text } = await res.json();
// Pass text to your LLM
```

```python
import requests
res = requests.get(
    'https://promptary.dev/api/v1/prompts/YOUR_PROMPT_ID',
    headers={'Authorization': 'Bearer pk_live_YOUR_KEY'}
)
prompt_text = res.json()['text']
```

---

## Example file format

Each example file follows this structure:

```markdown
# [Title]

## Framework: [FRAMEWORK NAME]

## Fields

**Role:** ...
**Action:** ...
**Context:** ...
**Expectation:** ...

## Assembled Prompt

[The complete prompt text, ready to copy]

## Use in Promptary

[Link to the framework guide on promptary.dev]
```

---

## Contributing

Found a framework combination that works exceptionally well? Open a PR. Guidelines:
- One example per file
- Follow the existing file format exactly
- Use real, practical use cases — not toy examples
- Include the assembled prompt text

---

## Links

- [Promptary](https://promptary.dev) — the workspace
- [API Documentation](https://promptary.dev/docs/) — REST API reference
- [Framework Guides](https://promptary.dev/frameworks/) — detailed guide for each framework
- [Pricing](https://promptary.dev/pricing/) — free and paid plans

---

*Built by [Promptary](https://promptary.dev) · EU-hosted · No ads · Your prompts stay yours*
