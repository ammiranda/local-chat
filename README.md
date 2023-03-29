# Local Chat

This simple app that sets up a web interface to send messages to ChatGPT.


## How to use

First install all the requirements:

```
pip install -r requirements.txt
```

Make sure you have registered an OpenAI access key: https://platform.openai.com/ and set it as an environment variable:

```
export OPENAI_KEY=<your-key>
```

You can also populate the OpenAI access key in a `.env` file at the root of this repository which will be read on server start up.

Edit the [app.py](app.py) file and adjust the `MAIN_PROMPT` according to your needs.

Then run the app in your local network:

```
flask run --host=0.0.0.0 --port=5000
```

It should print out the URL you can use to access the app.

## License

The code is licensed under MIT.

## Warnings

Use at your own risk. Do not assume responses are truthful.
