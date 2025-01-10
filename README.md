# LangChain Google Generative AI + Calculator Tool

This project demonstrates how to use LangChain agents with tools to perform tasks using a custom calculator tool and Google Generative AI. The agent executes user inputs by selecting the appropriate tool to respond to queries, such as evaluating mathematical expressions or generating text responses.

## Example Run

### Greeting Response (Reply Tool Example):
**User Input:**
Hi

**Agent Output:**

Entering new AgentExecutor chain... 

I should respond to the greeting.

Action: reply Action Input: Hello! 

Observation: klzg Thought: I now know the final answer

Final Answer: Hello!
Finished chain. Hello


### Calculator Tool Example:
**User Input:**
What is the result of 15 divided by 3?


**Agent Output:**

Entering new AgentExecutor chain...
I need to perform a division operation. 
Action: calculator Action Input: 15 / 3 Observation: 5.0
Thought: I now know the final answer 

Final Answer: 5.0
Finished chain. 5.0
