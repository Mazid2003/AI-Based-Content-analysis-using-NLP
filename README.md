**📜 NLP-Based Query Retrieval from PDFs**

This project is a Natural Language Processing (NLP) web application that allows users to upload a PDF file and ask queries related to its content. The system processes the document, understands the context, and retrieves the most relevant text segments that answer the user's question.

**🔹 Features**

✅ Upload a PDF file as input.

✅ Ask queries related to the content of the uploaded document.

✅ Retrieves the most relevant answers from the document.

✅ Built using Flask for seamless integration between the NLP model and frontend.

**🔹 Project Structure**

📂 logo_detection_query_model.py → The NLP model that processes PDFs and retrieves relevant text.

📂 app1.py → The Flask backend, integrating the NLP model with the website interface.

📂 templates/ → Contains HTML files for input submission and displaying results.

📂 static/ → Holds CSS files and assets for styling the web app.

**🔹 Technologies Used**

Python (Flask, SentenceTransformers, FAISS, PyMuPDF)

HTML, CSS (Frontend design)

FAISS (Efficient similarity search)

Sentence Transformers (all-MiniLM-L6-v2) for semantic search
