# Prompt Accuracy Checker API

The Prompt Accuracy Checker is an application that analyzes the accuracy of prompts for stable diffusion. With the click of a button, users can submit a prompt and receive a percentage score indicating how detailed the prompt is. In addition to the score, users will also see an image related to the prompt and a short description of the prompt.

## Getting Started

To get started with the Prompt Accuracy Checker: 
Clone this repository and run `npm install` && `node server.js`

### Setting up your .env file
To use the OpenAI API in your project, you'll need to create a .env file locally and add your API key from [openAI](https://openai.com) to it. Here's how:

Create a new file in your project directory and name it **.env**

Add this variable into the file:
```
CHATGPT_API_KEY_SECRET=your_api_key_here
```

## Technologies Used
The Back-end of Prompt Accuracy Checker is built using NodeJS. The image generation and scoring is handled by a backend API that the front-end communicates with via GET requests.

## Contributing
If you would like to contribute to the Prompt Accuracy Checker, please fork this repository and submit a pull request with your changes.

## Acknowledgments
This project was inspired by the need to quickly and accurately assess the quality of prompts for stable diffusion. Thanks to OpenAI for providing the models used in the backend API.
