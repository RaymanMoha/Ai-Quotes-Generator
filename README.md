# AI Text and Image Generator

This project is a JavaScript-based application that uses OpenAI's API to generate text based on user inputs and fetches an image related to the generated text from Unsplash. The generated text and image are then displayed on a web page.

## How It Works

1. **Inputs**: Users provide their name, favorite activity, favorite place, and set a temperature value.
2. **Text Generation**: The provided inputs are used as prompts for OpenAI's API to generate text. The temperature parameter influences the randomness of the generated output.
3. **Image Fetching**: The generated text is used to fetch a related image from Unsplash's API.
4. **Display**: The generated text and associated image are displayed on the webpage.

## Usage

To use this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Ai-Quotes-Generator.git

   Set up API Keys:

OpenAI API: Obtain an API key from OpenAI and integrate it into the callOpenAIAPI function in utils.js.
Unsplash API: Get an API key from Unsplash and integrate it into the callUnsplashAPI function in utils.js.
Open index.html in a web browser or set up a local server using Node.js or Python.

Enter your name, favorite activity, favorite place, and adjust the temperature slider to generate text and fetch an associated image.
