# MultiPDF-Query
Chat PDF with Gemini is a modern web application built with Streamlit that allows users to interact with PDF documents using natural language queries. Leveraging the power of Google's Generative AI, the application enables users to extract and analyze information from PDF files, making it easier to find relevant content quickly.


# Technologies Used

- **Streamlit**: For creating an interactive web application.
- **PyPDF2**: To read and extract text from PDF files.
- **LangChain**: To handle text splitting, vector storage, and question-answering chains.
- **Google Generative AI**: For embeddings and conversational AI.
- **FAISS**: For fast similarity search and retrieval.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   https://github.com/Vedant1033/MultiPDF-Query.git
   ```

2. **Set Up Environment**:
   Install the required Python packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the project root and add your Google API key:
   ```
   GOOGLE_API_KEY=your_google_api_key_here
   ```

4. **Run the Application**:
   Start the Streamlit app:
   ```bash
   streamlit run app.py
   ```

