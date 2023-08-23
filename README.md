# MoviePitch

Quick start:

```
$ npm install
$ npm start
```

# MoviePitch

 MoviePitch is a web application that generates creative responses to movie outlines using the OpenAI text-davinci-003 model. It's a fun project that showcases the capabilities of text-davinci-003 with the "few shot approach method" and how it can generate engaging content based on input prompts and an image generated based on the concept.


## Features

- **Creative Movie Outline Responses:** # MoviePitch takes a movie outline as input and generates enthusiastic and creative responses to it. The responses mimic the tone of a movie executive giving feedback.

- **Real-time Interaction:** Users can enter their movie outline in a text input field, and the AI's response is dynamically displayed on the page without requiring a page refresh.

- **Visual Loading Feedback:** A loading animation is displayed while the AI processes the input and generates a response, providing a visually appealing and user-friendly experience.
- **Visual Loading Feedback:**  Receive a creative image related to your concept with related text.

## Usage

1. Clone this repository to your local machine.
2. Replace `process.env.OPENAI_API_KEY` in the `index.js` file with your actual OpenAI API key.
3. Open the `index.html` file in a web browser.
4. Enter a movie outline in the provided text area and click the "Send" button.
5. The AI's response to the outline will be displayed below.

## API Key Setup

To run the project, you need an OpenAI API key. Follow these steps to set it up:

1. Sign up or log in to your OpenAI account.
2. Create a new environment variable named `OPENAI_API_KEY` and assign your API key as its value.

## Dependencies
This project relies on the following technologies and libraries:

OpenAI text-davinci-003 : The powerful language model used to generate movie responses.
OpenAI JavaScript API: A JavaScript library for interacting with the OpenAI API.
Acknowledgments
This project was inspired by the capabilities of the text-davinci-003 model developed by OpenAI. Special thanks to the OpenAI team for their efforts in pushing the boundaries of natural language processing.

Happy Coding!
