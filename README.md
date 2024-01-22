# gdl-connect
This is the public repo for the 'Demo on AI' during the GDLConnect Day 

## **DISCLAIMER:** 
In this demo an OpenAI GPT-4 subscrioption to the API was used. In order to fully reproduce the work in this repo, you will need to have your own key. Some of the steps might be reproduced using another model altogether. For example on [Huggingface](https://huggingface.co/). If you want to learn more about using the OpenAI API functionalities, use cases and options see [The OpenAI API Docs](https://platform.openai.com/docs/api-reference)

## Setting up
In order to use an API key in a secret `.env` file, visit [this blogpost](https://dev.to/biplov/handling-passwords-and-secret-keys-using-environment-variables-2ei0) to see how you can set this up.

Use the requirments file to setup your own virtual environment. I used conda for doing this. See the [Conda Docs](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment) for more.

## Accessing APIs

API stands for Application Programming Interface and is a way to communicate to websites, databases and software from a terminal or via a programming language script. Many application on the internet use it to be able to communicate with the application in a more efficient and faster way. For a good start on what an API is and how it works, see [this wiki](https://nl.wikipedia.org/wiki/Application_programming_interface).

To use an API, it is essenstial that you master some programming skills. Many APIs have implementations in R and Python, and for this reason alone it will pay off to learn about programming.

## OpenAI API use case

In the demo we saw that we can we can extract information from a pdf file by uploading it into the ChatGPT GUI. But what if...we have hundreds, or even thousands of pdf files...It would be very tidious and labourious to extract specific info from them, using this approach. Luckely for us, there is a better and more efficient way.

## Steps
In the demonstartion below we will walk through the following steps:

 - Defining an environment variable containing the API key for interacting with OpenAI's GPT-4
 - Setting up a custum GPT in Python
 - Defining a prompt in Python
 - Launching the prompt against several documents (./pdf) - we will demo 1 to keep the costs low
 - Getting the results in a structured dataframe together


