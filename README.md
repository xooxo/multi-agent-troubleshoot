# multi-agent-troubleshoot
Demo for lablab.ai x IBM Generative AI Hackathon by TheProviders

Our solution is aimed at making troubleshooting in an automated manner and needing less human interaction by providing multiple agents installed on different components. Our design is as follows: The agent named Controller Agent is overseer and planner for other agents. Worker agents receive plans as prompts from Controller agent and they are tasked with executing the plan using appropriate commands on their respective server. Commands can range from collecting logs to executing network commands. Agents are not responding to unrelated prompts such as "What is the Scrödinger Equation?" via specially crafted instructions to prevent answering unrelated prompts. 

Our solution can be effective in shorten troubleshooting of commonly faced problems in IT by AI agents capable of solving those problems. It is designed as to have little-to-no user interaction. Furthermore, future plan includes adding real-time monitoring to predict and prevent future issues by constantly feeding cluster metrics into Controller Agent and AI-driven capacity planning.

# Future Plans 
- Real-time Monitoring: Constantly fed metrics into Controller Agent
- More Tools: Currently, only ping is available to the agent
- Compatibility: More tools for wide range of OSes. Organizations have different server inventories and we need to cover more.


Note that for this demo, agents are in the same machine. 
