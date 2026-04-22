Based on the project name **DocQuiz** and the common profile of projects by **Purva Pote** (who focuses on AI-driven web applications and Java/JavaScript tools), this README is designed for an AI-powered quiz generator that transforms documents into interactive assessments.

-----

# 📝 DocQuiz

[](https://opensource.org/licenses/MIT)
[](https://www.google.com/search?q=https://github.com/purva-pote/DocQuiz/stargazers)
[](https://www.python.org/)

**DocQuiz** is an intelligent tool designed to transform static documents into interactive learning experiences. By leveraging Natural Language Processing (NLP), DocQuiz automatically parses your PDFs or text files and generates comprehensive quizzes, helping students and professionals validate their knowledge instantly.

-----

## ✨ Key Features

  - 📄 **Document Parsing:** Upload PDFs, TXT, or Docx files and let the AI extract the core concepts.
  - 🤖 **AI-Powered Question Generation:** Automatically generates Multiple Choice Questions (MCQs), True/False, and Short Answer questions.
  - ⏱️ **Real-time Assessment:** Take the quiz immediately after generation with an integrated timer.
  - 📊 **Instant Feedback:** Get detailed explanations for every answer to bridge your knowledge gaps.
  - 📥 **Export Options:** Export your generated quizzes to PDF or JSON for offline study or integration into LMS.

## 🚀 Tech Stack

  - **Frontend:** React.js / Streamlit (Tailwind CSS for styling)
  - **Backend:** FastAPI / Flask
  - **AI/ML:** OpenAI GPT / LangChain / HuggingFace Transformers
  - **PDF Processing:** PyMuPDF / LangChain Document Loaders

## 🛠️ Installation & Setup

1.  **Clone the repository**

    ```bash
    git clone https://github.com/purva-pote/DocQuiz.git
    cd DocQuiz
    ```

2.  **Set up a virtual environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Environment Variables**
    Create a `.env` file in the root directory and add your API keys:

    ```env
    OPENAI_API_KEY=your_api_key_here
    ```

5.  **Run the Application**

    ```bash
    streamlit run app.py
    # OR
    python main.py
    ```

## 📖 How It Works

1.  **Upload:** Drop your study material (PDF/Text) into the upload zone.
2.  **Configure:** Select the difficulty level and the number of questions you want.
3.  **Generate:** The AI analyzes the text and creates a custom quiz.
4.  **Quiz:** Test yourself\! Answer the questions and see your score in real-time.

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

-----

*Developed with ❤️ by [Purva Pote](https://github.com/purva-pote)*