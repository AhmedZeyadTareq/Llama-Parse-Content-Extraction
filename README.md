# 🧠 Llama-Parse-Content-Extraction

A powerful Streamlit application that leverages LlamaParse and OpenAI's GPT models to extract and analyze content from various file formats including PDFs, text files, and images. Features intelligent document processing with interactive AI-powered chat capabilities.

## ✨ Features

- **Multi-format Support**: Process PDF, TXT, JPG, and PNG files
- **AI-Powered Extraction**: Uses LlamaParse for intelligent content extraction
- **Interactive Chat**: Ask questions about your uploaded documents
- **Content Download**: Export extracted content as TXT files
- **User-friendly Interface**: Clean and intuitive Streamlit interface

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- OpenAI API key
- LlamaParse API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AhmedZeyadTareq/Llama-Parse-Content-Extraction.git
cd Llama-Parse-Content-Extraction
```

2. Install the required packages:
```bash
python -m venv venv
venv\Script\activate
pip install -r requirements.txt
```

3. Set up .env file with API keys:
```toml
OPENAI_API_KEY = your-openai-api-key
LLAMA_API_KEY = your-llamaparse-api-key
```

### Usage

1. Run the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL

3. Upload your file (PDF, TXT, JPG, or PNG)

4. Click "Start 🔁" to extract content

5. Ask questions about the extracted content using the chat interface

## 🛠️ How It Works

1. **File Upload**: Users can upload documents in supported formats
2. **Content Extraction**: LlamaParse processes the file and extracts text content
3. **AI Analysis**: OpenAI's GPT model analyzes the content and answers user questions
4. **Interactive Chat**: Users can ask multiple questions about the document content

## 📋 Supported File Types

- **PDF**: Documents and reports
- **TXT**: Plain text files
- **JPG/PNG**: Images with text content

## 🔧 Configuration

The application uses GPT-4.1-mini model by default. You can modify the `LLM_MODEL` variable in the code to use different OpenAI models.

## 📁 Project Structure

```
Llama-Parse-Content-Extraction/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── .streamlit/
│   └── secrets.toml      # API keys (not included in repo)
└── formal image.jpg      # Logo image
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🔒 Security

- API keys are stored securely using Streamlit secrets
- Temporary files are automatically cleaned up after processing
- No sensitive data is stored permanently

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Eng. Ahmed Zeyad Tareq**
- 📌 Data Scientist
- 🎓 Master of AI Engineering
- 📷 Instagram: [@adlm7](https://www.instagram.com/adlm7)
- 🔗 LinkedIn: [Ahmed Zeyad Tareq](https://www.linkedin.com/in/ahmed-zeyad-tareq)
- 🔗 GitHub: [Ahmed Zeyad Tareq](https://github.com/AhmedZeyadTareq)
- 🔗 Kaggle: [Ahmed Zeyad Tareq](https://www.kaggle.com/ahmedzeyadtareq)

## 🆘 Support

If you encounter any issues or have questions, please open an issue on GitHub or contact the author through the provided social media links.

## 🙏 Acknowledgments

- OpenAI for providing the GPT models
- LlamaIndex team for the LlamaParse library
- Streamlit for the amazing web framework
