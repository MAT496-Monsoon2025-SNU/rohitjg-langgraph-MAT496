# Module 1

## Video 1 - Motivation:

We learned that LangGraph lets us combine the reliability of fixed control flows (chains) with flexibility of agents. It enables building structured customizable and partially autonomous AI systems. (There is no code for this video)

## Video 2 - Simple Graph

We learnt abot graph state, and created a function to track textual difference and timestamp each time a node updates.

What's changed: Added user_name, mood, previous_graph_state, diff, and last_updated into node outputs and the State type. Implemented a minimal graph runner so graph.invoke works, and replaced duplicate cells with a single biased decide mood.
