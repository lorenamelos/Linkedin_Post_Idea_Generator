# Tutorial: Building a Simple LinkedIn Post Ideas Generator Agent

## Overview

In this tutorial, you will:

- Set up your Python environment.
- Create a LangGraph that defines a simple state machine.
- Integrate Anthropic’s API (using a Claude model) to generate creative post ideas.
- Run the agent to interactively generate LinkedIn post ideas.

*This example leverages LangGraph to manage the application flow while Anthropic’s LLM (Claude) produces the text.*

## Prerequisites

- **Python 3.8+**
- **API key for Anthropic**:
  - Sign up and obtain your API key from the Anthropic Console [Anthropic Docs](https://docs.anthropic.com/en/api/getting-started)
 
## How to

- Follow the guidance on the Jupyter Notebook attached and enjoy!

## Conclusion

In this tutorial we built a simple agent using LangGraph and Anthropic’s API to generate creative LinkedIn post ideas.

This modular design allows you to expand the agent further by:
- Adding more nodes (e.g., for reviewing or editing responses).
- Incorporating memory to maintain multi-turn conversations.
- Integrating additional tools (such as web search) to enhance idea generation.

For further reading:
- [Anthropic API Documentation](https://docs.anthropic.com/en/home)
- [LangGraph Tutorials and Documentation](https://langchain-ai.github.io/langgraph/tutorials/)
  
Feel free to experiment and customize the agent to suit your specific needs!
