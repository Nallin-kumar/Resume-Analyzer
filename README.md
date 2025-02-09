📄 Resume Analyzer Using NLP (Python Project)
This project is a Resume Analyzer built with Python, designed to automatically evaluate resumes based on extracted skills, work experience, and relevant entities. It uses Natural Language Processing (NLP) techniques to analyze PDF resumes and provides a score along with an interview recommendation.

🚀 Features
📤 Upload PDF Resumes directly in Google Colab.
🔍 Extract Skills, Organizations, and Dates using NLP techniques.
🗂️ Named Entity Recognition (NER) with spaCy to identify key entities.
📊 Automatic Scoring System based on identified skills and experience.
✅ Interview Recommendation based on the candidate’s overall score.

🛠️ Tech Stack
Python
NLTK (Natural Language Toolkit for tokenization)
spaCy (for NLP and Named Entity Recognition)
pdfminer.six (for PDF text extraction)
Google Colab (for interactive execution)

⚡ How It Works
Upload a PDF resume in the Colab notebook.
The system extracts text from the resume using pdfminer.six.
It identifies key skills, organizations, and dates using spaCy and NLTK.
A score (out of 100) is calculated based on the identified data.
The system provides an interview recommendation based on the score.

⚡ Scoring Criteria
Skills Identified: +5 points each
Organizations Detected: +3 points each
Dates Mentioned: +2 points each
Maximum Score: 100

Interview Recommendation:
✅ Recommended if score ≥ 60
❌ Not Recommended if score < 60

🚀 Future Enhancements
Support for DOCX files.
Exporting analysis reports as PDFs.
Advanced scoring algorithms with adjustable weights.
Adding customizable skill sets for different job roles.

📜 License
This project is licensed under the MIT License.
