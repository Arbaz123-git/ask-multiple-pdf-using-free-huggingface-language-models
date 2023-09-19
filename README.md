# ask-multiple-pdf-using-free-huggingface-language-models

Creating a Langchain App to chat with multiple PDF files using the Huggingface Language Models and as well as with ChatGPT API 

Building a powerful chatbot that allows you to ask questions about your multiple PDFs using LangChain and OpenAI .

Powered by ChatGPT, an advanced AI language model, our chatbot implementation enables you to interact with your PDF documents in a whole new way. We will also explore the utilization of Huggingface language models to enhance the chatbot's performance.

# How it Works 
The application follows these steps to provide responses to your questions:

1. PDF Loading: The app reads multiple PDF documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passes to the language model, which genrates a response based on the relevant content of the PDFs.

Dependencies and Installation 
To install the MultiPDF APP , please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command
   pip install -r requirements.txt

3. Obtain an API key from OpenAI and add it to the .env file in the project directory.

   OPENAI_API_KEY=your_secret_api_key

Usage 

To use the MultiPDF Chat App , follow these steps 

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the .env file

2. Run the main.py file using the Streamlit CLI. Execute the following command:

   streamlit run app.py

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.(File upload will be depend on your system memory ; more memory more files you can load and less memory then small and less file you can load)

5. Ask questions in natural language about the loaded PDFs using the chat interface.  
6. 

NOTE : IF YOU HAVE OPENAI API KEY SUBSCRIPTION THEN YOU CAN MAKE THIS PROJECT WITH OPENAI IF YOU DONT HAVE USE HUGGINGFACE LLMs.
