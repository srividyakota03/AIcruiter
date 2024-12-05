# AIcruiter - AI-Powered Resume Screening Tool

AIcruiter is an AI-powered resume screening tool that allows candidates to evaluate their fit for a job before applying. By comparing a job description with the content of a resume, the tool provides instant feedback on whether the resume matches the job requirements. This helps reduce rejections and boosts the confidence of job applicants.

## Features

- **Job Description and Resume Upload**: Upload a job description in text format and a resume in PDF format.
- **Resume Analysis**: The tool compares the uploaded resume with the job description and provides feedback.
- **Instant Feedback**: Get an instant message indicating whether your resume is suitable for the job.
- **User-Friendly Interface**: Simple and intuitive interface to upload files and get results.

## Technologies Used

- **Flask**: A lightweight Python web framework for building the web application.
- **Ngrok**: Used to expose the Flask server to a public URL for easy testing.
- **PyPDF2**: A Python library for extracting text from PDF files.
- **HTML/CSS**: For the frontend user interface with custom styling.
- **Google API**: For sending emails and scheduling interviews (optional for future updates).

## Requirements

- Python 3.x
- Flask
- Flask-Ngrok
- PyPDF2
- Werkzeug
