Simple command line app that uses langchain memory to store conversational data.

Utilizes langchain, open AI, and an auto-generated "messages" json file to store conversational data.

To get started, run `pip install pipenv`, or, depending on your environment, run
`pip3 install pipenv`.

Create a `.env` file in the root directory with the following variable:

```
OPENAI_API_KEY=your_openai_api_key
```

Then, run `pipenv shell` to bring up the virtual environment.

Finally, run `python main.py` to start the app.
