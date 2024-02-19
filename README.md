Learning LangChain
==================

Run notebooks
-------------

Copy `notebooks/.env_sample` to `notebooks/.env`:

```
cp notebooks/.env_sample notebooks/.env
```

Edit `notebooks/.env` and put your OpenAI API key (and the SerpApi key for the code that need it).

To obtain API keys:

- OpenAI: https://platform.openai.com/
- SerpApi: https://serpapi.com/

To open and run the notebooks you can use Docker:

```
cd notebooks
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work jupyter/datascience-notebook:python-3.10
```

In your web browser, go to the URL shown in the output.
