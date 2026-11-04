# GenAI Failure Modes and Limitations

## Introduction

Generative AI systems can produce useful content, but their responses are not always accurate or reliable.

Understanding common failure modes is important when using AI for technical documentation.

## 1. Hallucinations

A hallucination occurs when an AI model generates information that sounds convincing but is incorrect or unsupported.

**Example:**

A user asks for a Java method that does not exist. The model may generate a plausible-looking method name.

**How to reduce the risk:**
- Verify generated code against official documentation.
- Check technical claims using reliable sources.
- Avoid treating AI responses as guaranteed facts.

## 2. Stale Context

Stale context occurs when an AI system relies on outdated information or previously supplied details that no longer apply.

**Example:**

A developer changes an API endpoint, but the AI continues using the previous endpoint in its documentation.

**How to reduce the risk:**
- Provide updated project information.
- Remove outdated instructions.
- Verify generated documentation against the latest implementation.

## 3. Ambiguous Prompts

An unclear prompt can produce irrelevant or incomplete responses.

**How to reduce the risk:**
- Clearly define the task.
- Specify the target audience.
- Provide relevant context.
- Mention the expected output format.

## 4. Overconfident Responses

AI systems may express incorrect information with confidence.

**How to reduce the risk:**
- Independently verify important claims.
- Ask for supporting references where appropriate.
- Review technical output before publishing.

## 5. Privacy and Data Security

Sensitive information should not be unnecessarily included in prompts.

**Best practices:**
- Never include passwords or API keys.
- Remove personal information where possible.
- Follow organizational data security policies.

## Conclusion

GenAI can support technical writing, but human review remains essential. Accuracy, context, privacy, and verification should be considered before publishing AI-generated content.
