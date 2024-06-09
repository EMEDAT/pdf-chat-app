# pdf-chat-app
A fully responsive pdf-chat app lets you upload your pdf and chat with an ai reviewer (Bob) based on the content of the pdf document.
![pdf_chat_app](https://github.com/EMEDAT/pdf-chat-app/assets/101255406/cf23f4db-b3c3-4c59-a121-f148c1be4a70)
The app is built with Next.js. It uses PDF.js to parse and preview the PDF file, and the NVIDIA Nim API with the mixtral-8x7b-instruct-v0.1 AI model to chat with the PDF text.

First, duplicate the .env file into a new file named .env.local. Update the value of your NVIDIA Nim API key and Clerk key there.
