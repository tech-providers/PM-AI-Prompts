# Prompt Design Principles

This document defines the core principles used to design prompts in this repository.

The objective is to ensure prompts remain **clear, reliable and reusable**, while minimizing ambiguity and unnecessary complexity.

These principles guide how prompts should be written and structured.

---

# 1. Clarity over complexity

Prompts should prioritize clarity.

Instructions must be:

- direct
- unambiguous
- easy to follow

Avoid overly long instructions or unnecessary context that does not contribute to the task.

A clear prompt usually produces better results than a complex one.

---

# 2. Define the role

When appropriate, the prompt should define the role the model must assume.

Example:

"You are an expert Product Management assistant."

Role definition helps guide the reasoning style and context used by the model.

---

# 3. Define the task clearly

Every prompt should clearly state:

- what the model must do
- what type of output is expected

Example:

"Analyze the meeting transcript and extract key decisions and action items."

Avoid vague instructions such as:

"Help with this document."

---

# 4. Structure the process

For complex tasks, instructions should be broken into steps.

Example:

1. Analyze the input content.
2. Identify key information.
3. Organize the information clearly.
4. Generate the structured output.

Step-by-step instructions improve reliability and consistency.

---

# 5. Control the output structure

Prompts should clearly define how the output must be structured.

Example:

Meeting Summary  
Key Decisions  
Action Items  
Open Questions

When a template is provided, the model must follow the template exactly.

---

# 6. Support multilingual workflows

Prompts must support multilingual use cases.

Rules:

- The output language must match the language of the input.
- Templates must preserve their original language.
- Generated content must respect the language used in the source material.

---

# 7. Avoid hallucinations

Prompts should explicitly instruct the model not to invent information.

Example:

"Do not add information that is not present in the input."

If the information is missing, the model should indicate it instead of generating assumptions.

---

# 8. Include validation steps

Prompts should include a final validation stage.

The model should verify:

- the structure is correct
- the language matches the input
- the output contains the relevant information

This helps reduce incomplete or inconsistent responses.

---

# 9. Design for reuse

Prompts should be written in a way that allows them to be reused across different contexts.

Avoid instructions that depend on a single scenario unless strictly necessary.

Reusable prompts increase the long-term value of the prompt library.

---

# 10. Keep prompts maintainable

Prompts should remain easy to modify over time.

Avoid excessive internal complexity.

If a prompt becomes difficult to understand or maintain, it should be simplified.

---

# Final note

This repository is a collection of practical prompts designed to support workflows in Product Management and related activities.

The goal is not to create perfect prompts, but to create prompts that are **useful, understandable and adaptable over time**.
