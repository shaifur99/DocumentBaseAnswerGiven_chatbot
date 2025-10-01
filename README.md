# DocumentBaseAnswerGiven_chatbot

A smart question-answering chatbot that reads your Word document and answers questions based on its content. Perfect for students, teachers, or anyone who wants to quickly find information from their textbooks or documents.

## What Does It Do? 

- **Reads Word Documents:** Upload any `.docx` file (like your Class 5 English textbook)
- **Answers Questions:** Ask any question about the document content
- **Smart Search:** Finds the most relevant information using AI
- **Easy Interface:** Simple web interface that anyone can use

## How It Works 

1. **Document Processing:** Reads your Word file and breaks it into manageable chunks
2. **AI Understanding:** Uses sentence embeddings to understand the meaning of the text
3. **Smart Matching:** Finds the most relevant sections when you ask a question
4. **Answer Extraction:** An AI model extracts the exact answer from the relevant text

## Installation & Setup 

### Prerequisites

- Python 3.7+
- A Word document (`.docx`) you want to query

### Quick Start (Using Google Colab - Recommended)

1. **Open in Colab:**
   - Upload the notebook to Google Colab

2. **Run the Setup:**
   ```bash
   # The notebook will automatically install all required packages
   # Just run all cells sequentially


Upload Your Document:

When prompted, upload your Word file (.docx). The system will process it automatically.

Start Asking Questions:

A web interface will open

Type your questions and get instant answers!

Local Installation
 <img width="666" height="229" alt="image" src="https://github.com/user-attachments/assets/8ff07d8d-906e-4270-ac30-123e4a0f1ba2" />


Usage Examples

Character Questions: "Who is the main character in the story?"

Plot Questions: "What happened when they visited the forest?"

Factual Questions: "When was the company founded?"

Descriptive Questions: "What does the magical garden look like?"


<img width="656" height="159" alt="image" src="https://github.com/user-attachments/assets/031fb317-c72c-446a-9708-305188350a53" />

Features

Document Intelligence: Understands context from your specific document

Fast Responses: Uses efficient similarity search for quick answers

No Training Required: Works immediately with any Word document

Web Interface: User-friendly Gradio interface

Free to Use: Built with open-source technologies

Supported File Formats

Microsoft Word Documents (.docx)

Currently supports Word format only (other formats coming soon)

Technology Stack

Python-docx: Document reading and processing

Sentence Transformers: Text embedding and understanding

FAISS: Efficient similarity search

Hugging Face Transformers: Question-answering AI model

Gradio: Web interface development

Project Structure


<img width="656" height="183" alt="image" src="https://github.com/user-attachments/assets/666f2d22-93dc-4109-b71e-3e411fc45702" />


Limitations & Notes

     Works best with well-structured, factual content

    Answer quality depends on how clearly the information is presented

    May not perform well with very complex or ambiguous questions

    First run will download AI models (~300MB)

Contributing

    Feel free to contribute:

    Add support for more file formats (PDF, TXT)

    Improve the user interface

    Enhance the answer quality

    Add more language support

License

MIT License

Get Help

    Ensure your Word file is not corrupted

    Ensure all dependencies are properly installed

    Try rephrasing your questions more clearly

About the Developer

    This project was created to help students learn more effectively by making textbook content easily accessible   through natural conversation.



