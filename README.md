# prompt-engineering-guide

## Prompt structure:

| Block    | Component   |
|----------|-------------|
| Preamble | Context     |
|          | Instruction |
|          | Examples    |
| Input    | Input       |

## Best practices
  - Design with simplicity
  - Use Instructions over Constraints
  - Use variables in prompts
  - Adapt to model updates
  - mix up the classes examples in n-shot prompting
  - Experiment with output formats
  - Working with Schemas
  - Structure prompts with XML tags (e.g. <instructions>, <context>, <input> ...)
  - Separate data and instructions

## Prompting techniques

### SET CLEAR GOALS
  - Use action goals
  - Define length & format
  - Specify audience

### PROVIDE CONTEXTUAL INFORMATION
  - Include relevant information
  - Handing documents
  - Define key terms and concepts
  - Give AI a persona(role), a tone and writing style
  - Ask to reframe the question as a foundational principle first

### USE N-SHOT PROMPTING
  - (input) -> (output) examples
  - Style/tone examples
  - Examples of different levels of completions (e.g. beginner, advanced, intermediate ...)

### SPECIFICITY
  - Precise language/Straight to the point
  - Quantify request
  - Break down big concepts into smaller ones
  - Define boundaries
  - Break down long sentences

### EXPERIMENT AND PLAY AROUND
  - Different key words or formulations
  - Different level of detail
  - Different query length
    
### RELY ON CoT (chain of thought)
  - Encourage step by step reasoning
  - Ask model to explain reasoning process
  - Guide model through a sequence of logical thoughts

### RELY ON ToT (tree of thought)
  - Ask the model to consider multiple approaches before choosing one
  - Let the model self-evaluate its response
  - Backtracking/Search
    

Source: [Google: What is prompt engineering](https://cloud.google.com/discover/what-is-prompt-engineering) , [Qwiklabs-Courses: Prompt engineering](https://www.youtube.com/watch?v=5zoKVf-cnf4&t=400s) , [Google (Kaggle): Prompt Engineering](https://www.kaggle.com/whitepaper-prompt-engineering) , [Anthropic: Build with claude](https://platform.claude.com/docs/en/build-with-claude) [Anthropic (Github): Prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial/tree/master)

