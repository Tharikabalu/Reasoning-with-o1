# Reasoning-with-o1

The o1 model is exceptionally good at abstract reasoning tasks, achieving record-breaking performance in various domains such as:

- **Planning**
- **Coding**
- **Analyzing**
- **Domain-specific reasoning** (e.g., law)
- **STEM subjects**

OpenAI utilized reinforcement learning to produce a model that leverages 'test-time compute' to enhance performance on many reasoning tasks. The o1 model autonomously employs 'chain-of-thought' processes to:

- Break problems into smaller steps
- Try multiple strategies
- Think through responses before returning them

## In This Repository

### Key Principles of Prompting with o1

- From "simple and direct" to "show rather than tell"
- Explore the differences in performance

### Multi-step Task Management

- o1 acts as an orchestrator:
  - Creates a plan
  - Hands it over to the 4o-mini model to execute the plan in sequence
  - Balances the trade-off between intelligence and cost

### Coding Tasks

- o1 is used for:
  - Building new applications
  - Editing existing code
  - Testing performance through a coding competition between o1-mini and GPT 4o

### Image Understanding

- Learn how o1 performs better with a hierarchy of reasoning:
  - Incurs latency and cost upfront
  - Preprocesses the image
  - Indexes with rich details for Q&A use later

### Meta-prompting

- Using o1 to improve prompts:
  - Apply to a customer support evaluation set
  - Iteratively use o1 to modify a prompt to enhance performance
