**Problem Statement**

Green technology provides sustainable energy solutions. Low-carbon sources like nuclear fusion, nuclear fission, and advanced battery storage serve as critical alternatives to fossil fuels, and complement intermittent renewable sources like wind and solar by stabilizing the electricity grid. Technologies such as fusion using clean fuels like hydrogen isotopes are highly environmentally friendly, and advancements in energy storage like solid-state batteries are significantly more sustainable than those dependent on environmentally challenging extraction of lithium or cobalt.

I created agents to do the most up-to-date research and give a summary. 

**Why agents?**

I implemented memory for the agents, so they remember the conversation with the user's research.

**Overall architecture?**

The overall architecture is multi-agent: a research agent and a summary agent. There's a root agent that orchestrates the workflow. 

**The Build -- what tools or technologies used**
I used the Google Search tool for the most updated research.
I used AgentTool to build the sub-agents.
For agent memory, I use InMemorySessionService for conversation and InMemoryMemoryService for memory. I used load_memory instead of preload-memory to save tokens and avoid searching memory when not needed.

**If I had more time, this is what I'd do**
I've implemented Agent2Agent on another project, but didn't do it for this project due to time. 
