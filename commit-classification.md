# Named Entity Extraction to JSON

## Framework: Few-Shot

## Fields

**Task:** Extract all named entities from the text and return them as a JSON object with keys: people, companies, locations, dates.

**Example 1:** Input: "Anthropic CEO Dario Amodei spoke at the AI Summit in San Francisco on June 15."
Output: {"people": ["Dario Amodei"], "companies": ["Anthropic"], "locations": ["San Francisco"], "dates": ["June 15"]}

**Example 2 (optional):** Input: "Promptary was founded in the Netherlands in 2026 by b4analytics."
Output: {"people": [], "companies": ["Promptary", "b4analytics"], "locations": ["Netherlands"], "dates": ["2026"]}

**Example 3 (optional):** Input: "The meeting between Sarah Chen and the Google team is scheduled for next Monday in Amsterdam."
Output: {"people": ["Sarah Chen"], "companies": ["Google"], "locations": ["Amsterdam"], "dates": ["next Monday"]}

**Output format:** Valid JSON only. No markdown fences, no explanation. If a category has no entities, return an empty array [].

**Rules:** Extract only entities explicitly named in the text. Do not infer or assume. Dates can be relative ("next Monday") — preserve them as written.

## Assembled Prompt

Task: Extract all named entities from the text and return them as a JSON object with keys: people, companies, locations, dates.

Example 1: Input: "Anthropic CEO Dario Amodei spoke at the AI Summit in San Francisco on June 15."
Output: {"people": ["Dario Amodei"], "companies": ["Anthropic"], "locations": ["San Francisco"], "dates": ["June 15"]}

Example 2 (optional): Input: "Promptary was founded in the Netherlands in 2026 by b4analytics."
Output: {"people": [], "companies": ["Promptary", "b4analytics"], "locations": ["Netherlands"], "dates": ["2026"]}

Example 3 (optional): Input: "The meeting between Sarah Chen and the Google team is scheduled for next Monday in Amsterdam."
Output: {"people": ["Sarah Chen"], "companies": ["Google"], "locations": ["Amsterdam"], "dates": ["next Monday"]}

Output format: Valid JSON only. No markdown fences, no explanation. If a category has no entities, return an empty array [].

Rules: Extract only entities explicitly named in the text. Do not infer or assume. Dates can be relative ("next Monday") — preserve them as written.

## Use in Promptary

→ [Few-Shot Framework Guide](https://promptary.dev/frameworks/fewshot/)
