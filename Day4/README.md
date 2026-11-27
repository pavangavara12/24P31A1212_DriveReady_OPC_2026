# Day 4 – Tools, Structured Output and Google Sheets

## Overview

Day 4 focuses on making AI agents more useful by allowing them to use tools, generate structured outputs, and store information in Google Sheets.

We use the Sweet Crumbs Home Bakery example to understand how an AI agent can interact with real-world business operations.

## Topics Covered

### 1. Tools in LangChain
- Learned what tools are and why AI agents need them.
- Used the `@tool` decorator to convert Python functions into LangChain tools.
- Created tools to retrieve bakery product details and prices.
- Tested tools using `.invoke()`.

### 2. Structured Output with Pydantic
- Learned why structured output is important.
- Used Pydantic `BaseModel` to define a bakery order format.
- Defined fields such as customer name, item, quantity, date, and eggless preference.
- Used `with_structured_output()` to generate structured order information.
- Tested valid and invalid customer inputs.

### 3. Google Sheets Integration
- Connected Google Sheets with Python using `gspread`.
- Created a spreadsheet to store bakery orders.
- Added order details such as name, item, quantity, date, eggless preference, and total price.
- Created a `log_order` tool to save orders automatically.

### 4. Testing Tool Selection
- Tested how an AI agent selects tools based on their names and descriptions.
- Changed a tool's name and description to observe how tool selection is affected.
- Understood why clear tool names and descriptions are important.

### 5. Understanding Agent Traces
- Inspected the messages generated during agent execution.
- Identified AI messages and tool calls.
- Understood how an LLM decides to call a tool and receives its result.

## Technologies Used

- Python
- Google Colab
- Groq API
- GPT-OSS-20B
- LangChain
- Pydantic
- Google Sheets
- gspread

## Key Takeaways

- Tools allow AI agents to perform actions.
- Pydantic helps validate and structure data.
- Google Sheets can store customer orders.
- Clear tool descriptions improve tool selection.
- Agent traces help us understand how an agent works.

## Conclusion

In Day 4, we learned how to build more capable AI agents using tools, structured output, and Google Sheets integration. We explored how these components can be used in real-world business applications.
