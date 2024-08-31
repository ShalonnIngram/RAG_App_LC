# Chat With Your Internal Documents
Click the image above to watch the demo video.

https://github.com/user-attachments/assets/d7f58c9d-edb8-41cf-b55a-7502621221d2


## Overview

This AI Powered Internal Applications querys the content of documents by:
- Allows users to chat with multiple documents simultaneously
- Acceptable formats include: .txt, .pdf, .docx, .pptx, .csv, .xlsx
- Tech Stack: OpenAI Embeddings/LLM Model gpt-4o-mini, Vector Database Chroma, Streamlit for UI

<img width="1125" alt="Screenshot 2024-08-31 at 12 01 29 AM" src="https://github.com/user-attachments/assets/13b1a246-14ee-4194-b181-682718628c70">



# Streamlit User Interface

<img width="1393" alt="Screenshot 2024-08-30 at 11 51 55 PM" src="https://github.com/user-attachments/assets/940c934c-56dc-4ef0-baef-0acd0dbbe8f3">


# Project Structure

- `app.py`: Main application script.
- `.env`: file which will contain your environment variable.
- `requirements.txt`: Python packages required for working of the app.
- `README.md`: Project documentation.
## Dependencies

- PyPDF2
- langchain
- Streamlit
- OpenAI
- dotenv
- **Note:** This project requires Python 3.10 or higher.

# Instructions
- updated the .env file with your OpenAI credentials
- start a virtual environment
- run code and access application  `
- select browse files
- select the process button
- add query to text box to query documents
- select the get respsonse button

1. Clone the repository:
   ``bash
     git clone https://github.com/your-username/your-repository.git

   ```bash
     pip install -r requirements.txt
   ```bash
   streamlit run main.py
   ```bash
    ``bash
   streamlit run main.py
