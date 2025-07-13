# helpful-prompts-in-life

Prompts that helps with my life, such as summarizing emails, answering kid's questions, etc. Updates whenever needed.

I often use ChatGPT so prompts may work better in GPT than other LLMs. However, I hope the prompts will stay 

## Context: Starting a New Chat Window

Many LLMs claim to have long context window sizes. However, [this paper](https://arxiv.org/html/2404.02060v3) suggested that LLMs still struggles with long context for complex tasks.

Therefore I usually started a new chat when asking about long context questions, e.g. to summarize a PDF or a long article.

## Anthropic Prompt Guide Recommendation for visual / frontend code generation ([link](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/claude-4-best-practices#enhance-visual-and-frontend-code-generation))

```text
Don't hold back. Give it your all.
```

## OpenAI o1-mini model

- I found the model to be very verbose, so at the beginning of each section, I will put this initial prompt:

```text
For the rest of this conversation, DO NOT go over than 3 paragraphs for explanation unless there is an absolute need for complex subjects or answers. Please be concise.
```

## Checking emails

### Email Summarization

- Summarize software engineering work or business emails

```text
Forget about previous articles or instructions. Imagine you are a market research partner of a world-class Venture Capital Firm like Sequoia Capital. Please summarize this article: 
<Article Title>
<Article Body>
```

- Summarize emails for kid's school

```text
Please summarize this email for <title> for kid's parents, ideally with different bullet points for different action items or subjects:
<email body>
```
