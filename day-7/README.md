
:: Create your First AI Agent with zero coding


https://github.com/gouthamkamre68/ai-assisted-devops/tree/main/day-7


https://www.youtube.com/watch?v=fLWP5d-1jiM&list=PLdpzxOOAlwvJ_qWyuqhbHteY84O1qr72a&index=9


AI Assistance will use for conversation but cannot implement the task behalf

AI Agent will do the task (bolt.new/GitHub copilot workspace) behalf you (https://bolt.new/)


Frameworks to create AI Agent
1) Autogen
2) langgraph
3) CrewAI


: Task: Research latest trends in the field of Kubernetes and to write a blog(MD) file which summarize top 10 important trends that your organization has to focus.


prerequisites:-

https://docs.crewai.com/en/installation

Install Python >=3.10 and <3.14
install ollama and pull llama3.1:latest    



#mkdir crew-example
#cd crew-example
#python3 -m venv crew          # create virtual env name is crew
#source crew/bin/activate        # activate the environment

#deactivate                      # to remove venv

#pip3 install crewai

#crewai create crew devops-ai-project         #devops-ai-project  is project name

 enter ollama number and next select model of ollama


#ollama list

open mai.py  and change everywhere from "topic": "AI LLM" to "topic": "Kubernetes" 

Start by editing agents.yaml and tasks.yaml to define your crew’s behavior.


#crewai install               # it will setup 

#crewai run

#cat report.md




