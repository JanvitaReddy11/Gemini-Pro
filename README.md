# Multiple-PDF Reader

This project leverages the capabilities of Streamlit, PyPDF2, and Google Generative AI to create an interactive application that allows users to upload multiple PDF files, process the text, and ask questions based on the content.

Download all the necessary packages from the reuirements.txt file
-- pip install -r requirements.txt
-- streamlit run app.py

The application will open in your browser. Use the sidebar menu to upload multiple PDF files. Click the 'Submit' button to process the uploaded PDFs. The application will extract text, split it into chunks, and create a vector store for efficient text retrieval. Enter the question in the text input field on the main page. The question-answering chain will generate a detailed answer based on the context of the retrieved documents.
    
