# ai-powered-legal-research-assistant-
 ##  Project Overview
 The AI-Powered Legal Research Assistant is a Streamlit-based tool designed to assist in extracting and
 analyzing legal information from image-based documents. By leveraging OCR, spelling correction, keyword
 extraction, and OpenRouters DeepSeek model, this assistant provides legal insights and answers to user
 queries in real-time.--
##  Features-  Upload legal document images-  OCR-based text extraction using Tesseract-  Spelling correction using SymSpell-  Legal keyword detection-  AI-powered legal insight generation (DeepSeek model via OpenRouter)-  Legal Q&A chatbot--
##  Tech Stack- **Frontend**: Streamlit- **Backend**: Python- **Machine Learning/NLP**:
  - Tesseract OCR
  - SymSpell for spell correction
  - OpenAI (via OpenRouter) with DeepSeek model- **Others**:
  - pdf2image
  - PIL (Pillow)
  - dotenv--
##  Installation
 1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/legal-research-assistant.git
   cd legal-research-assistant
   ```
 2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
 3. **Set up environment variables**  
   Create a `.env` file and add:
   ```env
   OPENAI_API_KEY=your_openrouter_api_key
   ```
 4. **Download & configure Tesseract and Poppler**
   - Install [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
   - Install [Poppler](http://blog.alivate.com.au/poppler-windows/) (for PDF support)
 5. **Run the app**  
   ```bash
   streamlit run app.py
   ```--
##  Directory Structure
 ```
 legal-research-assistant/
 app.py                   # Streamlit application
 en-80k.txt               # Dictionary file for SymSpell
 requirements.txt         # Dependencies
 README.md                # Project documentation
 .env                     # API key (not included in repo)
 ```--
##  How It Works
 1. User uploads a legal document image.
 2. Text is extracted using Tesseract OCR.
 3. Text is corrected using SymSpell.
 4. Relevant legal keywords are extracted.
 5. A query is sent to DeepSeek model for contextual legal analysis.
 6. The user can also chat with the AI to ask legal questions.--
##  Model Evaluation
 | Metric               | Value     |
 |----------------------|-----------|
 | OCR Accuracy         | ~85-90%   |
 | Correction Precision | ~92%      |
 | AI Relevance         | Subjective (contextual accuracy) |
 | Latency              | ~2-5 sec  |--
##  Legal Keywords Used- Complaint  - Corruption  - Vigilance  - Harassment  - Police  
*...and more*
 You can expand the keyword list based on your legal domain needs.--
##  Future Improvements-  Support full PDF document parsing-  Integration with Indian Kanoon or SCC Online-  Multilingual legal support-  Case law recommendation engine
--
##  References- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)  - [SymSpell](https://github.com/wolfgarbe/SymSpell)  - [Streamlit](https://streamlit.io)  - [OpenRouter](https://openrouter.ai)  - [Indian Kanoon](https://indiankanoon.org/)--
##  Disclaimer
 This project is for educational purposes only and **does not constitute legal advice**. Always consult a
 qualified legal professional for real-world legal matters.--
##  Author
 **Moulishwaran**  
*Data Science & AI Enthusiast | LegalTech Innovator*
