:: AI Agent for your Internal Documentation

https://www.youtube.com/watch?v=Naw35ovkXGc&list=PLdpzxOOAlwvJ_qWyuqhbHteY84O1qr72a&index=11


AI agents : Crew AI, Autogen, Langgraph   


prerequisites:-

https://docs.crewai.com/en/installation

Install Python >=3.10 and <3.14
install ollama and pull llama3.1:latest    



#python3 -m venv osai          # create virtual env name is osai
#source osai/bin/activate        # activate the environment

#pip3 install crewai

#crewai create crew docs-agent         #docs-agnet  is project name

 enter ollama number and next select model of ollama



: Always check example instead writing from the scratch.

git clone git@github.com:crewAIInc/crewAI-examples.git

#cd crewAI-examples

move your pdf in the folder "crewAI-examples/crews/meta_quest_knowledge
/knowledge/"


Go to config/agents.yaml



Goutham_tool_expert:
  role: >
    Goutham Tool Expert
  goal: >
    Provide the best possible answers to questions about Goutham Tool
  backstory: >
    You're a seasoned expert in the world of Goutham Tool. You're known for your
    ability to provide the best possible answers to questions about this
    cutting-edge technology, ensuring that your audience is well-informed and
    satisfied with the latest advancements in the field.


Go to Task.yaml and  change meta query to Goutham Tool

Go to main.py

instead hardcoded questions in function get the input from the user

question = input("Please enter your question: ")
inputs = {
  "question" : question,
}


go to crew.py and update pdf name 

#pip instll uv

#crewai install
