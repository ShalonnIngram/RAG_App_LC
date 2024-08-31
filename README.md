# Chat With Your Internal Documents


## Overview

This AI Powered Internal Applications querys the content of documents by:
- Allows users to chat with multiple documents simultaneously
- Acceptable formats include: .txt, .pdf, .docx, .pptx, .csv, .xlsx
- Tech Stack: OpenAI Embeddings/LLM Model gpt-4o-mini, Vector Database Chroma, Streamlit for UI

<img width="1125" alt="Screenshot 2024-08-31 at 12 01 29 AM" src="https://github.com/user-attachments/assets/13b1a246-14ee-4194-b181-682718628c70">
<br>

## Demo
<a href="https://youtu.be/ztBJqzBU5kc">
  <img src="https://github.com/user-attachments/assets/c22b7111-9af9-4d4f-9490-8857befa4158" alt="Watch the video" width="100%">
</a>

[![Watch the video](path-to-thumbnail-image)]() <!-- Embed a video with a clickable image -->

Click the image above to watch the demo video.

## Screenshots

![Screenshot 1](path-to-screenshot-1) <!-- Example screenshot -->
<img width="1125" alt="Screenshot 2024-08-31 at 12 01 29 AM" src="https://github.com/user-attachments/assets/df89e423-341a-4e53-b193-62f43acaa657">


### Project Structure

- `app.py`: Main application script.
- `.env`: file which will contain your environment variable.
- `requirements.txt`: Python packages required for working of the app.
- `README.md`: Project documentation.

### Dependencies

- PyPDF2
- langchain
- Streamlit
- OpenAI
- dotenv
- **Note:** This project requires Python 3.10 or higher.

### Instructions
- updated the .env file with your OpenAI credentials
- start a virtual environment
- ```bash
   pip install -r requirements.txt
   ```
- run code and access application  ```bash
   streamlit run main.py
   ```
  `http://localhost:8501`
- select browse file
- select the process button
- add query to text box to query documents


1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
