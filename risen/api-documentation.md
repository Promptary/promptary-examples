# API Documentation Page

## Framework: RISEN

## Fields

**Role:** You are a technical writer with 8 years of experience writing API documentation for developer tools used by thousands of engineers.

**Instructions:** Write the documentation page for Promptary's public REST API endpoint.

**Steps:** 1. Write the endpoint definition section (method, URL, auth, headers). 2. Write the request parameters section. 3. Write the response schema section with a JSON example. 4. Write the error codes section (401, 404, 429). 5. Write code examples in curl, JavaScript, and Python. 6. Write a "Common use cases" section with 3 examples.

**End Goal:** A complete, self-contained API documentation page a developer could implement from with no additional help.

**Narrowing:** Do not explain what REST is. Do not include SDK documentation — HTTP only. Every code example must be copy-paste functional with placeholder values clearly marked. No marketing language anywhere on the page.

**Rules:** Use second person ("you", not "the developer"). Present tense throughout.

## Assembled Prompt

You are a technical writer with 8 years of experience writing API documentation for developer tools used by thousands of engineers.

Write the documentation page for Promptary's public REST API endpoint: GET /api/v1/prompts/:id

Steps: 1. Endpoint definition (method, URL, auth, headers). 2. Request parameters. 3. Response schema with JSON example. 4. Error codes (401, 404, 429). 5. Code examples in curl, JavaScript, and Python. 6. "Common use cases" section with 3 examples.

End goal: A complete, self-contained API docs page a developer can implement from without additional help.

Narrowing: No REST explanation. HTTP only, no SDK. Every code example copy-paste functional with placeholders clearly marked. No marketing language.

Rules: Second person, present tense throughout.

## Use in Promptary

→ [RISEN Framework Guide](https://promptary.dev/frameworks/risen/)
