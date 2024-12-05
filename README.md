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
  
## How to Use
**Launch the Application:**
After running the app, open the provided Ngrok URL or local URL in your browser.
Fill in Your Details: Enter your full name and email address in the provided fields.
Input the Job Description: Paste the job description text into the specified field.
Upload Your Resume: Upload your resume in PDF format (the system only accepts PDFs).
Get Instant Feedback: The AI will analyze the job description and your resume, providing immediate results, such as:
"YES": Your resume matches the job description (possible interview invitation).
"NO": Your resume doesn’t match the job description (polite rejection).

## Key Highlights
- **Instant Results:** Get feedback immediately after uploading your resume and job description.
- **AI-Powered:** AI algorithms help simulate the decision-making process of a recruiter.
- **Polite Communication:** Receive professional rejection emails or interview invitations.
- **Easy Integration with Google:** Future updates will allow sending interview invites directly through Google Calendar.
