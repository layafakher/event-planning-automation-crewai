
# Multi-Agent Event Planning System with CrewAI

This project demonstrates how to build an **AI-powered event planning system** using **CrewAI multi-agent architecture**.

The system coordinates multiple agents to plan and organize an event, simulating how real-world teams collaborate across different roles.

## Overview

Event planning involves multiple steps such as research, logistics, scheduling, and coordination. This project models that process using specialized AI agents working together.

Each agent is responsible for a specific part of the workflow, enabling structured and efficient planning.

## Agents

- **Event Planner** – defines the event concept, goals, and overall structure
- **Venue Coordinator** – identifies and evaluates suitable venues
- **Logistics Manager** – handles scheduling, resources, and execution details

Each agent contributes to a different layer of the planning pipeline.

## Key Features

- Multi-agent collaboration using CrewAI
- Role-based task decomposition
- Structured event planning workflow
- Clear separation of responsibilities
- Easily extendable to real-world applications

## Workflow

The system follows a sequential planning pipeline:

1. Define event concept and requirements
2. Research and select appropriate venue options
3. Plan logistics and execution details

Each step builds on the previous one, ensuring consistency across the plan.

## Technologies Used

- Python
- CrewAI
- crewai_tools
- LangChain (community)
- OpenAI GPT models
- Jupyter Notebook

## File

- `L5_tasks_event_planning.ipynb` – main notebook for event planning workflow

## Installation

Install dependencies:

```bash
pip install crewai crewai_tools langchain_community
````

Set your OpenAI API key before running.

## How to Run

1. Open the notebook:
   `L5_tasks_event_planning.ipynb`
2. Set your API key
3. Run all cells
4. Provide event details (type, audience, goals, etc.)
5. Execute the crew workflow
6. Review the generated event plan

## Example Use Cases

* Conference planning
* Workshop organization
* Corporate event coordination
* Academic or research events

## Learning Objectives

This project helps you understand:

* how to design multi-agent workflows for complex tasks
* how to break down real-world problems into agent roles
* how CrewAI manages task sequencing and collaboration
* how structured pipelines improve LLM outputs

## Future Improvements

* Add budget optimization
* Integrate real venue APIs
* Include scheduling/calendar tools
* Add user interaction loop
* Deploy as a web application

## Notes

* Outputs may vary between runs
* Designed as a prototype and educational example
* Uses a sequential multi-agent workflow

## License

For educational and demonstration purposes.

```




If you want next (very powerful for your GitHub profile):
- I can unify **ALL 4 projects into one portfolio README**
- Or write a **“Projects” section for your resume** using these  
- Or create a **diagram for each (architecture figure)** 🚀
```
