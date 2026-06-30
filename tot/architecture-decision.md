# Infrastructure Scaling Decision

## Framework: Tree-of-Thought

## Fields

**Problem:** A SaaS product running on a single 4GB VPS (Hetzner) is growing and needs to decide how to scale when traffic increases 10x. Current stack: Node.js, PostgreSQL, Nginx. Three options: (1) vertical scaling — upgrade to larger VPS, (2) horizontal scaling — add app servers behind a load balancer, (3) managed services — migrate to Railway/Render/Fly.io.

**Number of branches:** Explore all 3 scaling approaches.

**Evaluation criteria:** Evaluate on: (1) operational complexity for a solo developer, (2) cost at 10x traffic, (3) time to implement, (4) risk of downtime during migration.

**Selection:** Score each 1–5 per criterion. Show the table. Recommend the option that minimizes operational burden while handling 10x traffic. Include the specific signal (metric or event) that should trigger implementation.

**Rules:** Assume the solo developer has no DevOps experience beyond basic Linux administration. Cost estimates must be concrete (€/month ranges), not vague. The trigger signal must be a specific measurable threshold.

## Assembled Prompt

Problem: A SaaS product running on a single 4GB VPS (Hetzner) is growing and needs to decide how to scale when traffic increases 10x. Current stack: Node.js, PostgreSQL, Nginx. Three options: (1) vertical scaling — upgrade to larger VPS, (2) horizontal scaling — add app servers behind a load balancer, (3) managed services — migrate to Railway/Render/Fly.io.

Number of branches: Explore all 3 scaling approaches.

Evaluation criteria: Evaluate on: (1) operational complexity for a solo developer, (2) cost at 10x traffic, (3) time to implement, (4) risk of downtime during migration.

Selection: Score each 1–5 per criterion. Show the table. Recommend the option that minimizes operational burden while handling 10x traffic. Include the specific signal (metric or event) that should trigger implementation.

Rules: Assume the solo developer has no DevOps experience beyond basic Linux administration. Cost estimates must be concrete (€/month ranges), not vague. The trigger signal must be a specific measurable threshold.

## Use in Promptary

→ [Tree-of-Thought Framework Guide](https://promptary.dev/frameworks/tot/)
