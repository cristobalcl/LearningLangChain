FROM jupyter/datascience-notebook:python-3.9

# Install langchain[llms] and python-dotenv
RUN pip install langchain[llms] \
    && pip install python-dotenv

# Set the working directory
WORKDIR /home/jovyan/work
