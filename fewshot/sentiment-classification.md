# Customer Feedback Sentiment Classification

## Framework: Few-Shot

## Fields

**Task:** Classify each customer support message into exactly one sentiment category: Positive, Neutral, or Negative.

**Example 1:** Input: "Just upgraded to the Developer plan and the API is working perfectly. This is exactly what I needed."
Output: Positive

**Example 2 (optional):** Input: "Can you tell me how many API keys I get on the Team plan?"
Output: Neutral

**Example 3 (optional):** Input: "I've been trying to get my API key to work for three hours. This is completely broken."
Output: Negative

**Output format:** Return only the label: Positive, Neutral, or Negative. No explanation, no punctuation, nothing else.

**Rules:** Every message gets exactly one label. Do not return "Mixed" or any label not in the three categories.

## Assembled Prompt

Task: Classify each customer support message into exactly one sentiment category: Positive, Neutral, or Negative.

Example 1: Input: "Just upgraded to the Developer plan and the API is working perfectly. This is exactly what I needed."
Output: Positive

Example 2 (optional): Input: "Can you tell me how many API keys I get on the Team plan?"
Output: Neutral

Example 3 (optional): Input: "I've been trying to get my API key to work for three hours. This is completely broken."
Output: Negative

Output format: Return only the label: Positive, Neutral, or Negative. No explanation, no punctuation, nothing else.

Rules: Every message gets exactly one label. Do not return "Mixed" or any label not in the three categories.

## Use in Promptary

→ [Few-Shot Framework Guide](https://promptary.dev/frameworks/fewshot/)
