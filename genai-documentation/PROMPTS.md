# GenAI Prompt Engineering Guide

## Introduction

Prompt engineering is the process of designing clear instructions for Generative AI systems to produce useful and relevant responses.

A well-structured prompt provides context, defines the task, and specifies the expected output.

## 1. Zero-Shot Prompting

Zero-shot prompting asks an AI model to complete a task without providing examples.

**Example:**

```text
Explain REST APIs in simple English.
Use a beginner-friendly explanation
and provide one practical example.
```

**When to use:**
- General explanations.
- Simple question answering.
- Basic content generation.

## 2. Few-Shot Prompting

Few-shot prompting provides examples to guide the model's output.

**Example:**

```text
Convert technical terms into simple explanations.

Example 1:
Input: API
Output: A way for software applications to communicate.

Example 2:
Input: Database
Output: A system used to store and organize information.

Now explain:
Input: Cloud Computing
```

**When to use:**
- Consistent formatting.
- Repeated classification tasks.
- Structured content generation.

## 3. Role-Based Prompting

Role-based prompting assigns a role or perspective to the AI model.

**Example:**

```text
Act as a technical documentation writer.

Explain how a REST API works
for a beginner developer.

Use:
- Simple English
- Short paragraphs
- Practical examples
```

**When to use:**
- Audience-specific explanations.
- Technical documentation.
- Educational content.

## 4. Characteristics of a Good Prompt

A useful prompt should contain:

1. Context – Background information.
2. Task – What the model should do.
3. Constraints – What it should avoid.
4. Output format – How the answer should be structured.

## Conclusion

Effective prompt engineering improves the clarity, relevance, and consistency of AI-generated responses. However, generated content should always be reviewed for factual accuracy.
