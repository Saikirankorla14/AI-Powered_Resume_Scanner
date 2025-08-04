# AI-Powered_Resume_Scanner

📌 Project Overview
The AI-Powered Resume Scanner is an intelligent application that extracts skills and experience from resumes and matches them with job descriptions. This tool is designed to streamline the recruitment process by enabling automated, intelligent candidate screening.
🛠️ Tools & Technologies
- NLP Libraries: SpaCy, BERT (Transformers)
- Frontend: Streamlit (for interactive UI)
- Backend: Python
- Dataset: Custom dataset created by scraping LinkedIn profiles (ensure compliance with site terms or use dummy data)
✨ Features
- Resume text extraction and parsing
- Named Entity Recognition (NER) for skill and experience extraction
- Job description parsing
- Similarity matching between resumes and job descriptions
- Streamlit interface for interactive scanning and ranking
📈 Workflow
1. Upload or parse a resume (PDF/DOCX).
2. Extract relevant entities such as skills, experience, and qualifications using SpaCy/BERT.
3. Parse job description using NLP techniques.
4. Calculate similarity scores using cosine similarity or other metrics.
5. Display ranked matches via a Streamlit dashboard.
⚙️ Installation
1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Run `streamlit run app.py`
🚀 Future Enhancements
- Integration with online resume sources (e.g., Google Drive, LinkedIn API)
- Smart recommendations for job seekers
- Support for multiple file formats and languages
