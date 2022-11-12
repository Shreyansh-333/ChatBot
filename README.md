
# Chatbot

This is a chatbot for general conversations. It is a flask application written in Python and JavaScript. To deploy the project in your system, follow the instructions provided. If you're feeling lonely, engage in some light conversation. Demand coffee, jokes, or riddles!


## Authors

- [@Shreyansh-333](https://github.com/Shreyansh-333)

## Deployment

To deploy this project, clone the repository->
```bash
  $ git clone https://github.com/Shreyansh-333/ChatBot.git
```
Move to the repository and create a virtual environment:
- For windows
```bash
> python3 -m venv [Virtual Environment Name]
> .\[Virtual Environment Folder Name]\Scripts\activate
```
- For Unix or Mac
```bash
> python3 -m venv [Virtual Environment Name]
> source [Virtual Environment Name]/bin/activate
```
Now install some required dependencies and packages:
```bash
$ ([Virtual Environment Name]) pip install Flask torch torchvision nltk
```
```bash
$ ([Virtual Environment Name]) python
>>> import nltk
>>> nltk.download('punkt')
```
Train the chatbot. You can insert your own questions with answers for chatbot in intents.json.
```bash
$ (venv) python train.py
```

Now to run the chatbot on terminal, use the following command:
```bash
$ (venv) python chat.py
```
To run the flask app, write:
```bash
$ (venv) flask run
```
It will open a webpage on local port. Happy chatting!
