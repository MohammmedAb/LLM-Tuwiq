# Assignmnet 1 Answers

## 1. Hugging Face Agents

### Why We need Hugging Face Agents?
Large language models in thier basic form are just a prediction models that predict the next word in a sequence of words. But in more complex taks that need a hight level of logic like Math, they often fail. This is where Agents come in. Agents can give the main model a set of tools to use for a specific task. For example:

- For Math, the agent can give the model a calculator.
- For data visualization, the agent can give the model a code eviroment to run the code and visualize the data.
- For web search, the agent can give the model a web browser to search the web.
- For image generation, the agent can give the model a set of tools to generate images. 

### Hugging face Agents
**Hugging face provides a set of agents that can be used for different tasks. Some of the agents are:**

-  CodeAgent: one shot agent, generate code for a given task and execute it at once.
- RecipeAgent: This agent generate a multi-step plan, have an observer to check the progress of the plan and can generate a feedback until the plan is completed successfully.

## 2. Hugging Face Pipeline for Text Generation
Higging face Pipeline provide an abstraction for language models inference, It handles all the preprocessing and postprocessing steps for the model such as:
- Tokenization
- Padding
- Decoding

## 3. HF Inference Endpoints
Provide a way to use the model on the cloud and use it as an API. This is useful so you can use the model without having to download it. (This is useful for large models)

## 4. Image Generation and Explore Different Models Available on the Hugging Face Website



# Assignmnet 2 Answers
