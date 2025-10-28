:: Docker Model Runner

: Install docker desktop latest version

https://docs.docker.com/ai/model-runner/

https://hub.docker.com/r/ai/


#docker model -h           #to see the docker model

#docker model pull ai/smollm2:latest


#docker model list

#docker model run ai/smollm2 "what is docker ?"               # used for single prompt


# docker model run ai/smollm2             # to start interactive chat

#docker model rm ai/smollm2                 #  to remove model


:Integration application with docker model (https://github.com/docker/hello-genai)


#git clone https://github.com/docker/hello-genai.git         # clone on local

#cd hello-genai

#vi .env         #        Set llm model which available on your machine
LLM_MODEL_NAME=ai/smollm2

#./run.sh       


Open your browser and visit the following links:

http://localhost:8080 for the GenAI Application in Go

http://localhost:8081 for the GenAI Application in Python

http://localhost:8082 for the GenAI Application in Node

http://localhost:8083 for the GenAI Application in Rust



