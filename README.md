# HireGenius AI - Open Source Job Application Assistant 🚀

## Overview

[HireGenius AI](https://verbose-halibut-6996p99qrgj7crj96-8501.app.github.dev/) is an AI-powered job application assistant that automates job scraping, resume matching, and email generation. It is designed to streamline the hiring process for recruitment teams in leading companies like Infosys, TCS, and Accenture, helping them attract top engineering talent from industry leaders such as Google, Microsoft, and Amazon.

## Features ✨

- **Job Posting Scraper** 📌: Extracts job descriptions from various job portals.
- **Resume Matching** 📊: Uses AI to analyze and compare resumes with job requirements.
- **Automated Email Generation** ✉️: Generates professional application emails tailored to job postings.
- **Visualization** 📈: Provides insights on job-resume match percentage with graphical representation.
- **Open Source & Extensible** 🛠: Fully customizable and open for contributions.

## Project Link 🔗

[HireGenius AI Web App](https://verbose-halibut-6996p99qrgj7crj96-8501.app.github.dev/)

## Technologies Used 🛠

- **Python** 🐍
- **Streamlit** 🎨 ([Streamlit Docs](https://docs.streamlit.io/))
- **BeautifulSoup** 🌐 ([BeautifulSoup Docs](https://www.crummy.com/software/BeautifulSoup/bs4/doc/))
- **Matplotlib** 📊 ([Matplotlib Docs](https://matplotlib.org/))
- **Regex** ✍️
- **DeepSeek AI API** 🤖 ([DeepSeek API](https://api.deepseek.com))

## How It Works 🔍

1. **Enter Job Posting URL**: The AI fetches job details from the given link.
2. **Upload Resume**: The AI compares your resume with the job description.
3. **Analyze & Score**: It calculates a match percentage and visualizes it.
4. **Generate Application Email**: AI drafts a professional email based on extracted job details.

## Installation & Setup 🏗

### Prerequisites
- Python 3.8+
- Virtual Environment (Recommended)

### Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/hiregenius-ai.git

# Navigate to the project directory
cd hiregenius-ai

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

## API Configuration 🔑

The application uses the **DeepSeek AI API** for AI-powered email generation. Get your API key from [DeepSeek AI](https://api.deepseek.com) and update the `DEEPSEEK_API_KEY` in `app.py`.

```python
DEEPSEEK_API_KEY = "your_api_key_here"
client = openai.OpenAI(api_key=DEEPSEEK_API_KEY, base_url="https://api.deepseek.com")
```

## Contribution 🤝

We welcome contributions from developers, AI enthusiasts, and recruiters! To contribute:

1. Fork the repository 🍴
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m 'Add feature XYZ'`
4. Push to the branch: `git push origin feature-branch`
5. Open a Pull Request 🛠

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact 📬

For queries and collaborations:

- **Email**: [tariqeesha@gmail.com](mailto:tariqeesha@gmail.com)
- **GitHub**: [Your GitHub Profile]((https://github.com/codewithEshaYoutube/)

---
🚀 _HireGenius AI - Making job applications effortless with AI!_
