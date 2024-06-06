# Introduction

This project is about creating a chatbot for your pdf files using Flask, a popular web framework, and the Langchain, another popular framework for working wtih Large Language Models (LLMs). The chatbot will not just interact with users via text but also comprehend and answer questions related to the content of a specific document. 

# Flask

Flask is a lightweight and flexible web framework for Python, known for its simplicity and speed. A web framework is a software framework designed to support the development of web applications, including the creation of web servers, and managing HTTP requests and responses. Flask is used to create the server side or back-end of our chatbot. This involves handling incoming messages from users, processing these messages, and sending appropriate responses back to the user.

# Langchain

Langchain is a versatile tool for building AI-driven language applications. It provides various functionalities such as text retrieval, summarization, translation, and many more, by leveraging pre-trained language models. In this project, we will be integrating Langchain into our chatbot, empowering it to understand and respond to diverse user inputs effectively.

# Chatbots

Chatbots are software applications designed to engage in human-like conversation. They can respond to text inputs from users and are widely used in various domains, including customer service, eCommerce, and education. In this project, you will build a chatbot capable of not only engaging users in a general conversation but also answering queries based on a particular document.

# Routes in Flask

Routes are an essential part of web development. When your application receives a request from a client (typically a web browser), it needs to know how to handle that request. This is where routing comes in.
In Flask, routes are created using the @app.route decorator to bind a function to a URL route. When a user visits that URL, the associated function is executed. In our chatbot project, we will use routes to handle the POST requests carrying user messages and to process document data.

# HTML - CSS - Javascript

A ready-to-use chatbot front-end, built with HTML, CSS, and Javascript. HTML structures web content, CSS styles it, and Javascript adds interactivity. These technologies create a visually appealing and interactive chatbot interface.

# Learning Objectives

- Understand the basics of langchain and AI applications
- Set up a development environment for building an assistant using Python Flask
- Implement PDF upload functionality to allow the assistant to understand file input from users
- Integrate the assistant with OpenAI’s GPT-3 model to give it a high level of intelligence and the ability to understand and respond to user requests
- (Optional) Understand how to deploy the PDF assistant to a web server for use by a wider audience

# Prerequisites

Having knowledge of the basics of HTML/CSS, Javascript, and Python are nice to have but not essential.

# Setting Up and Understanding the User Interface

In this project, the goal is to create an interface that allows communication with a chatbot, and a backend to manage the sending and receiving of responses.

Set up the environment by running following lines:

1. pip3 install virtualenv
2. virtualenv my_env # create a virtual environment my_env
3. source my_env/bin/activate # activate my_env

The front-end will use HTML, CSS and Javascript with popular libraries such as Bootstrap for basic styling, Font Awesome for icons and JQuery for efficient handling of actions. The user interface will be similar to many of chatbots you see and use online. The code for the interface is provided and the focus of the guided project is on connecting this interface with the backend where we handle the uploading of your custom documents and integrating it with a LLM model to get customised responses. The provided code will help to understand how the front-end and back-end interact, and learn about the important parts and how it works, giving a good understanding of how the front-end works and how to create this simple web page.

Run the following commands to receive the project, and rename it to proper name, and finally move into that directory by running followings:

1. git clone https://github.com/sinanazeri/build_chatbot_for_your_data-design-.git
2. mv build_chatbot_for_your_data-design- build_chatbot_for_your_data
3. cd build_chatbot_for_your_data

installing the requirements for the project:

1. pip install Flask Flask_Cors langchain==0.0.299 openai==0.28 pdf2image chromadb==0.4.15 pypdf tiktoken

The next section gives a brief understanding of how the front end works.

# HTML, CSS, and Javascript
The index.html file is responsible for the layout and structure of the web interface. This file contains the code for incorporating external libraries such as JQuery, Bootstrap, and FontAwesome Icons, as well as the CSS (style.css) and Javascript code (script.js) that control the styling and interactivity of the interface.

The style.css file is responsible for customizing the visual appearance of the page’s components. It also handles the loading animation using CSS keyframes. Keyframes are a way of defining the values of an animation at various points in time, allowing for a smooth transition between different styles and creating dynamic animations.

The script.js file is responsible for the page’s interactivity and functionality. It contains the majority of the code and handles all the necessary functions such as switching between light and dark mode, sending messages, and displaying new messages on the screen. It even enables the users to record audio.
