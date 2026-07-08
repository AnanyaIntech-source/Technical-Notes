## 📝 Prompt Engineering Notes

This document contains concise notes and important concepts related to **Prompt Engineering**. It serves as a quick revision guide covering prompt design principles, prompting techniques, best practices, and real-world applications of Large Language Models (LLMs).

---

## 📌 What is Prompt Engineering?

Prompt Engineering is the process of designing clear, structured, and effective prompts that guide an AI model to generate accurate, relevant, and useful responses.

A **prompt** is the input provided to an AI model.

Good prompts improve:

- Accuracy
- Relevance
- Consistency
- Reasoning
- Response Quality

---

## 📌 Why Prompt Engineering Matters

Well-designed prompts help AI:

- Understand user intent
- Reduce hallucinations
- Produce structured responses
- Follow instructions correctly
- Generate higher-quality outputs

---

## 📌 Components of a Good Prompt

A good prompt usually contains:

- **Role**
- **Task**
- **Context**
- **Constraints**
- **Output Format**

Example:

```
You are a career advisor.

Help a second-year Computer Science student prepare a roadmap for AI and Cloud Computing.

Provide the answer in a table.
```

---

## 📌 Prompt Structure

```
Role

↓

Task

↓

Context

↓

Constraints

↓

Expected Output
```

---

## 📌 Types of Prompting

### Zero-Shot Prompting

The model is given only the task.

Example:

```
Explain cloud computing.
```

##

### One-Shot Prompting

One example is provided.

Example:

```
Question:
2 + 2 = 4

Now solve:

5 + 7 = ?
```

##

### Few-Shot Prompting

Multiple examples are provided before asking the model to perform a task.

Useful for:

- Classification
- Formatting
- Pattern learning

##

### Chain-of-Thought Prompting

Encourages the model to solve problems step by step.

Example:

```
Solve the problem step by step.
```

Useful for:

- Mathematics
- Logical reasoning
- Programming

##

### Role Prompting

Assigning a role to the AI.

Examples:

```
You are a software engineer.

You are an Azure architect.

You are a cybersecurity analyst.
```

##

### Instruction Prompting

Clearly tells the model what to do.

Example:

```
Summarize this article in five bullet points.
```

---

## 📌 Prompt Design Principles

Good prompts should be:

- Clear
- Specific
- Concise
- Context-rich
- Goal-oriented

Avoid:

- Ambiguous wording
- Multiple unrelated tasks
- Missing context

---

## 📌 Prompt Template

```
Role:

Task:

Context:

Constraints:

Output Format:
```

Example:

```
Role:
Career Mentor

Task:
Create a learning roadmap.

Context:
Second-year Computer Science student interested in AI and Cloud.

Output:
Table with timeline.
```

---

## 📌 Common Prompting Techniques

- Zero-shot
- One-shot
- Few-shot
- Chain-of-Thought
- Role Prompting
- Step-by-Step Prompting
- Structured Prompting

---

## 📌 Prompt Optimization

Improve prompts by:

- Adding context
- Specifying the audience
- Defining the output format
- Limiting response length
- Providing examples
- Breaking large tasks into smaller ones

---

## 📌 Prompt Iteration

Prompt engineering is an iterative process.

```
Prompt

↓

AI Response

↓

Evaluate

↓

Improve Prompt

↓

Better Response
```

---

## 📌 Hallucinations

A hallucination occurs when an AI model generates information that appears correct but is factually incorrect or unsupported.

Reduce hallucinations by:

- Providing sufficient context
- Asking factual questions
- Using reliable sources
- Breaking complex tasks into smaller prompts

---

## 📌 Tokens

Large Language Models process text as **tokens** rather than complete words.

Examples:

```
Artificial Intelligence

↓

Artificial

↓

Intelligence
```

Token usage affects:

- Cost
- Response length
- Processing speed

---

## 📌 Temperature

Temperature controls the randomness of AI responses.

| Temperature | Behaviour |
|-------------|-----------|
| 0.0 | Deterministic |
| 0.2 | Very focused |
| 0.7 | Balanced |
| 1.0 | Creative |
| >1 | Highly random |

---

## 📌 Top-p Sampling

Top-p controls the range of possible next words chosen by the model.

Lower values:

- More focused

Higher values:

- More creative

---

## 📌 Best Practices

✅ Be specific

✅ Provide context

✅ Define the desired output

✅ Use examples

✅ Ask one task at a time

✅ Iterate and refine prompts

---

## 📌 Real-World Applications

- Chatbots
- Code Generation
- Document Summarization
- Content Creation
- Resume Analysis
- Customer Support
- Research Assistance
- AI Agents

---

## 📌 Popular LLMs

- GPT-4
- GPT-5
- Microsoft Copilot
- Claude
- Gemini
- Llama
- Mistral

---

## 📌 Key Terms

| Term | Meaning |
|------|---------|
| Prompt | Input provided to an AI model |
| Token | Small unit of text processed by the model |
| LLM | Large Language Model |
| Hallucination | Incorrect AI-generated information |
| Temperature | Controls randomness |
| Context Window | Maximum amount of information processed at once |

---

## 💡 Key Takeaways

- Prompt Engineering is essential for obtaining high-quality AI responses.
- Good prompts are clear, specific, and provide sufficient context.
- Different prompting techniques are suitable for different tasks.
- Iterative refinement improves response quality.
- Prompt Engineering is a core skill in modern Generative AI development.

---

### 🛠️ Hands-on Practice

- ✅ Designed structured prompts
- ✅ Practiced role prompting
- ✅ Used chain-of-thought prompting
- ✅ Experimented with temperature settings
- ✅ Refined prompts to improve AI responses

---

## Status

🟢 Active | Continuously Updated

---

## License

This repository is protected under the Creative Commons Attribution 4.0 International License.
All certificates belong to the author and are displayed here for educational and professional documentation purposes.

---

## Contact

**Ananya Siju**  
[LinkedIn](https://www.linkedin.com/in/ananya-siju-a04835291/) | [GitHub](https://github.com/AnanyaIntech-source) | ananyasiju16@gmail.com

---

> **Author:** [Ananya Siju](https://github.com/AnanyaIntech-source)
> 

