# 😎💬😎 LLM Converse with PDF App

Welcome to the **LLM Chat App**! This app allows you to have interactive conversations with an LLM-powered chatbot using your PDF files. Below, you'll find all the information you need to get started.

## About
This app is powered by several amazing technologies:

- **Streamlit**: A user-friendly framework for building web applications with Python.
- **LangChain**: A powerful library for natural language processing tasks.
- **OpenAI**: The LLM model, an advanced language model that helps in answering your questions.

## Getting Started
To use this app, follow these simple steps:

1. **Clone the Repository**: If you haven't already, clone this GitHub repository to your local machine.

2. **Install Dependencies**: Make sure you have all the required Python packages installed. You can do this by running:

   ```bash
   pip install streamlit dotenv PyPDF2 streamlit_extras langchain
3. **Set Up Environment Variables**: This app uses environment variables for configuration. Create a .env file in the same directory as your code and add your OpenAI API key:
makefile
Copy code
   ```bash
    OPENAI_API_KEY=YOUR_OPENAI_API_KEY_HERE
4. **Run the App: Execute the following command to run the app locally**:
    ```bash
    streamlit run your_app_name.py
5. **Use the App**: Once the app is running, you'll see the sidebar with information about the app and its creator. You can upload your PDF file by clicking the "Upload your PDF" button. The app will process the PDF and allow you to ask questions about its content.

## Features
- PDF Upload: Upload your PDF file to the app.
- Question Asking: After uploading the PDF, you can type your questions in the text input field.
- Real-time Responses: The app uses the LangChain library and the OpenAI LLM model to provide real-time answers to your questions.
- Saved Results: For improved performance, the app saves the processed data to a pickle file, reducing processing time for future interactions.

## Credits
Prompt Engineer.
