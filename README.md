# Thinkpalm-agentai-SruthyMuraleedharan-LabD3
Assessment 1

Name : Sruthy Muraleedharan
Track: Backend Dev
Lab Name: LAB D3
What I have done:

I implemented a basic ReAct (Reasoning + Action) agent using the Groq API and a LLaMA model. In this implementation, the agent receives a user query and follows a structured format that includes Thought, Action, Action Input, Observation, and Final Answer. The Groq API key is used to authenticate and send requests to the LLM, which generates the reasoning steps. A simple calculator function is integrated as a tool, allowing the agent to perform mathematical operations when required. The agent processes the response, extracts the action and input, executes the tool, and feeds the observation back into the model for the next step. This loop continues until the final answer is generated. The entire solution is implemented in Python using Google Colab, making it easy to run and test without complex setup.

What it Does:

The program is a simple AI-based ReAct agent that can understand a user’s question and solve it step by step. It takes a query as input, such as a mathematical problem, and uses the Groq model to think and decide what action to perform. If the problem requires calculation, the agent uses a built-in calculator function to compute the result. It then combines its reasoning and the calculated result to generate a final answer. The program shows how an AI agent can not only respond to questions but also perform actions like calculations to give accurate results.
