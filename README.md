# AICTE-Tech-Saksham-Internship-Project

## AI-powered Resume Screening and Ranking System

### Overview
This project is an AI-powered Resume Screening and Ranking System designed to automate the process of filtering and ranking resumes based on relevant criteria. The system leverages Natural Language Processing (NLP) and Machine Learning (ML) techniques to extract and evaluate key information from resumes efficiently.

### Technology Stack

- **Frontend:** Built with Streamlit for an interactive and user-friendly interface.
- **Backend:** Python for backend processing and logic implementation.
- **AI & NLP:** 
  - `scikit-learn` for machine learning algorithms.
  - `NLTK` for Natural Language Processing tasks.
- **Resume Parsing:** `PyPDF2` for extracting text from PDF resumes.

### Features

- Extracts relevant data from resumes using NLP.
- Ranks resumes based on predefined criteria.
- Provides a user-friendly interface for recruiters to interact with the system.
- Uses AI-based techniques to improve resume evaluation accuracy.

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/AICTE-Tech-Saksham-Internship-Project.git
   cd AICTE-Tech-Saksham-Internship-Project
   ```
2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the application:**
   ```sh
   streamlit run resume-app.py
   ```

### Usage

1. Upload a resume (PDF format).
2. The system extracts key information using `PyPDF2`.
3. NLP and ML models analyze the content and rank resumes based on relevance.
4. Results are displayed interactively on the Streamlit interface.

### Contributing

We welcome contributions! Feel free to submit issues and pull requests.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Author

**Harshika Bansal**  
Connect with me on [LinkedIn](www.linkedin.com/in/harshika-bansal) | GitHub: [HarshikaBansal](https://github.com/harshikab2112)
