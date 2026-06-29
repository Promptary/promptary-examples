# Technical Architecture Review

## Framework: CRIT

## Fields

**Context:** I'm building a SaaS product on a single VPS (Hetzner, 4GB RAM, Ubuntu 24.04) running Node.js, PostgreSQL, Nginx, and several services. The product is growing and I need to understand when and how to scale the infrastructure.

**Role:** You are a senior infrastructure architect with 12 years of experience scaling SaaS products from single-server setups to distributed systems, with specific expertise in knowing when NOT to over-engineer.

**Interview:** Before giving architecture advice, ask me 4 questions to understand: current traffic levels and growth rate, which service is the current bottleneck, my budget constraints, and my tolerance for operational complexity.

**Task:** After the interview, provide: an assessment of how long the current setup can last, the first infrastructure change to make when limits are hit, the second change after that, and a clear signal (metric or event) that tells me it's time to make each change.

## Assembled Prompt

Context: Single VPS (Hetzner, 4GB RAM, Ubuntu 24.04) running Node.js, PostgreSQL, Nginx, and several services. Growing product, need to understand when and how to scale.

You are a senior infrastructure architect who specializes in scaling SaaS from single-server to distributed — with expertise in knowing when NOT to over-engineer.

Before giving advice, ask me 4 questions: current traffic and growth rate, current bottleneck, budget constraints, and tolerance for operational complexity.

After the interview: how long the current setup will last, the first infrastructure change to make, the second change after that, and the specific metric that signals it's time for each change.

## Use in Promptary

→ [CRIT Framework Guide](https://promptary.dev/frameworks/crit/)
