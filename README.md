# -Automated-Resume-Reviewer-ARR
An intelligent, LLM-powered application designed to parse, analyze, and optimize resumes against job descriptions. By leveraging advanced prompt engineering and text analysis, ARR provides job seekers and recruiters with instant, actionable insights on ATS compatibility, keyword gaps, and overall profile strength. 

Features

Resume Text Extraction: Extracts raw text from multi-page PDF documents.

AI-Powered Analysis: Leverages the Google Gemini API for deep contextual resume evaluation.

ATS Compatibility Score: Calculates a matching score between the candidate's profile and the job description.

Keyword Matching: Evaluates keyword overlap using mathematical text alignment models.

Improvement Suggestions: Provides concrete feedback to refine bullet points and increase impact.

Skill Gap Identification: Automatically flags missing technical skills and core competencies.

Report Generation: Exports the final evaluation and suggestions into text or PDF formats.

Technologies Used

Language: Python 3.x

AI Engine: Google Gemini API

Development Environment: Google Colab

NLP & Analytics: Scikit-learn (TF-IDF, Cosine Similarity)

Document Parsing: PyPDF2 / pdfplumber

Data Processing: Pandas & NumPy
