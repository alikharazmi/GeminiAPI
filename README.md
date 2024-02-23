# Gemini API Beginner's Guide and Generative AI Showcase

Welcome to the Gemini API Beginner's Guide and Generative AI Showcase repository! This project serves as a beginner-friendly introduction to working with the Gemini API and demonstrates how to obtain an API key. Additionally, it showcases the usage of the Gemini Generative AI model for various purposes.

## Obtain API key:
follow the link below to get your API key.
https://aistudio.google.com/app/apikey

## Dependencies:
`pip install -q -U google-generativeai`

## Quick cheatsheet:
 - Text output

`GenerativeModel('gemini-pro')` model and `generateContent` method to generate text output.

 - Text/image to text:
 
`GenerativeModel('gemini-pro-vision')` model and 'generate_content([prompt, img,…])' to generate text output

 - Text to chat

`GenerativeModel('gemini-pro')` model and `start_chat(history=[])` method to start chat, `send_message` method to send chat messages

 - Text to embedding:
`embed_content()` method and `embedding-001` model to generate embeddings

## Usage
### Gemini API:

Use gemini_api.py to interact with the Gemini API. This includes functionalities like fetching data, placing orders, and managing your account.
Make sure to replace the placeholder API keys with your actual keys.
### Generative AI:

generative_ai.py showcases how to use the Gemini Generative AI model. You can experiment with different inputs and see the generated outputs.
Feel free to explore and modify the script to suit your needs.
Contributions
Contributions to this project are welcome! If you have any improvements or additional features you'd like to add, please feel free to open a pull request.

## Support
If you encounter any issues or have questions about using the Gemini API or the Generative AI model, feel free to open an issue in the repository. We're here to help!

Happy coding! 🚀

