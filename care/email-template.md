# Transactional Email Template

## Framework: CARE

## Fields

**Context:** Promptary sends transactional emails for key events: account verification, password reset, API key creation, and plan upgrade confirmation. Each email needs to be clear, functional, and consistent in voice.

**Action:** Write the plan upgrade confirmation email that a user receives immediately after upgrading from Personal to Developer plan.

**Result:** A transactional email with subject line and body. Under 120 words. Confirms the upgrade, tells them the one most important thing they can do right now (create their first API key), includes a direct link. Functional, not promotional.

**Example:** Stripe's receipt emails — they confirm the transaction in the first sentence, give the relevant details in the second, and provide a single action link. No marketing. No upsell. Just the information the user needs at that moment.

## Assembled Prompt

Context: Promptary sends transactional emails for key events. Need the plan upgrade confirmation email.

Action: Write the plan upgrade confirmation email a user receives after upgrading from Personal to Developer plan.

Result: Subject line + body. Under 120 words. Confirms the upgrade, tells them the most important thing to do right now (create their first API key), includes a direct link. Functional, not promotional.

Example of the style: Stripe's receipt emails — confirm the transaction in sentence one, give relevant details in sentence two, provide a single action link. No marketing. No upsell.

## Use in Promptary

→ [CARE Framework Guide](https://promptary.dev/frameworks/care/)
