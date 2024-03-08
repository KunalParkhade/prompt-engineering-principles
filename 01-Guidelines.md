# **Prompting Principles**
- **Principle 1: Write clear and specific instructions**
- **Principle 2: Give the model time to “think”**

## Tactics
**Tactic 1: Use delimiters to clearly indicate distinct parts of the input**
- Triple quotes: """
- Triple backticks: ```
- Triple dashes: ---
- Angle brackets: <>
- XML tags: <tag> </tag>

**Tactic 2: Ask for structured output**
- JSON, HTML

**Tactic 3: Ask the model to check whether conditions are satisfied**

**Tactic 4: Few-short prompting**
- Give successful examples of completing tasks. Then ask model to perform the task.

# **Principle 2: Give the model time to "think"**

**Tactic 1: Specify the steps required to complete a task**
- Step 1:...
- Step 2:...
- 
-
- Step N:...

**Tactic 2: Instruct the model to work out its own solution before rushing to a conclusion**

## Model Limitations:
Hallucinations: Makes statements that sound plausible but are not true

Reducing hallucinations:
- First find relevant information then answer the question based on the relevant information 