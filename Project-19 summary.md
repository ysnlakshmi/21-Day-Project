This notebook explores the concept of AI Agents and the CrewAI framework. I've learned about the definition of compute and agentic AI, and why frameworks like CrewAI are gaining traction.

The core components of the CrewAI framework were explained:
- **Crew:** The overall system managing agents, processes, tasks, and outcomes.
- **AI Agents:** Intelligent entities that collaborate, make decisions, and use tools.
- **Tools:** External resources agents use to complete tasks.
- **Process:** Defines how agents collaborate and tasks are assigned.
- **Tasks:** Specific units of work for agents.

I also saw a mental framework mapping these components to real-world scenarios, like a "Data Science Product Research Department" (Crew) with "Market Research" and "Data Analyst" (Agents), using "Internet Search" (Tools) for tasks like "Collecting data."

Two experiments were demonstrated:
- **Experiment 1: Content Creation Workflow:** This involved a crew with a Planner, Writer, and Editor agent to create a blog post on Artificial Intelligence. The agents had specific roles, goals, and backstories, and tasks were defined for planning, writing, and editing the content.
- **Experiment 2: Customer Support Workflow:** This experiment showcased a crew with a Senior Support Representative and a Support Quality Assurance Specialist agent, using a web scraping tool to address a customer inquiry about setting up and kicking off a Crew with memory functionality.

Finally, I attempted to code a Market Analyst crew with a researcher and a writer agent using the CrewAI framework and a search tool. After installing the necessary libraries and setting up the environment, I defined the agents and their respective tasks: researching AI trends and writing a blog post based on the findings. The crew was set up to run sequentially. Although there were some errors during the execution related to tool usage and delegation, the market researcher agent successfully completed its task and generated a comprehensive report on AI trends. This report was then saved to a markdown file.