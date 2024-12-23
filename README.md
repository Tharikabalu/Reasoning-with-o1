# Reasoning-with-o1
The o1 model is exceptionally good at abstract reasoning tasks. It has record-breaking performance on tasks such as planning, coding, analyzing, domain-specific reasoning like law, and other STEM subjects.
OpenAI utilized reinforcement learning to produce a model that uses ‘test-time compute’ to improve performance on many reasoning tasks. o1 autonomously utilizes ‘chain-of-thought’ to break problems into smaller steps, try multiple strategies, and think through responses before returning them.
 
In this repo:
Four key principles of prompting using o1 from “simple and direct” to “show rather than tell,” and explore the difference in performance.
Multi-step task in which o1 acts as an orchestrator creating a plan and handing it over to the 4o-mini model to execute the plan in sequence, balancing the trade-off between intelligence and cost.
o1 for a coding task to build a new application, edit existing code, and test performance by running a coding competition between o1-mini and GPT 4o.
o1 for image understanding and learn how it performs better with a hierarchy of reasoning, in which it incurs the latency and cost upfront, preprocessing the image and indexing it with rich details so it can be used for Q&A later.
Meta-prompting, o1 to improve your prompts. Using a customer support evaluation set, iteratively use o1 to modify a prompt to improve performance.
