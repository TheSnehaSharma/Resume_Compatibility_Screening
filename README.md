<div align="center">

# Resume Compatibility Screening 🎯

**An intelligent, NLP-driven Applicant Tracking System (ATS) to bridge the gap between candidate profiles and job requirements.**

[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit App](https://img.shields.io/badge/Streamlit-Live_Demo-FF4B4B.svg?style=flat-square&logo=streamlit&logoColor=white)](https://cvscore.streamlit.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg?style=flat-square)](https://opensource.org/licenses/MIT)

[Live Demo](https://cvscore.streamlit.app/) • [Report Bug](https://github.com/TheSnehaSharma/Resume_Compatibility_Screening/issues)

</div>

---

## Overview
**Resume Compatibility Screening (CV Score)** is a lightweight, high-performance web application that simulates enterprise-grade ATS logic. By leveraging advanced Natural Language Processing (NLP), it evaluates a candidate's resume against a specific Job Description (JD) to instantly provide a match score, professional summary, and actionable skill gap analysis.

<img src="https://raw.githubusercontent.com/TheSnehaSharma/Resume_Compatibility_Screening/refs/heads/main/media/Screenshot%202025-05-01%20150454.png" alt="Application Interface Screenshot" width="100%">

## Core Features
* **Semantic JD Matching:** Context-aware analysis goes beyond basic keyword counting.
* **Quantitative ATS Scoring:** Generates a definitive, percentage-based compatibility score.
* **Skill Gap Analysis:** Extracts matched competencies and explicitly highlights missing JD keywords.
* **Intelligent Profiling:** Synthesizes a concise professional summary from unstructured PDF text.

## Tech Stack
* **Frontend & UI:** `Streamlit`
* **Core Logic:** `Python 3`
* **Document Processing:** `PyPDF2` & `pdfplumber`
* **AI & NLP Engine:** Generative AI (`Gemini API`)
* **Data Management:** `Pandas`
* **Deployment:** `Streamlit Community Cloud`

## Usage
1. **Upload Resume:** Navigate to the [https://cvscore.streamlit.app/](https://cvscore.streamlit.app/) and drop in a resume.
2. **Fill Job Description:** Paste the text of your target Job Description.
3. **Analyze:** Run the scan to instantly view the compatibility score, matched skills, and critical gaps.

---
*Distributed under the [MIT License](LICENSE).*
