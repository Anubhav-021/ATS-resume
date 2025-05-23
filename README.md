# ATS-resume
ATS Resume is a powerful AI-based web application that evaluates your resume against a job description. It uses Google's Gemini 1.5 Pro model to perform semantic analysis and calculates a percentage match, highlights missing keywords, and provides professional feedback based on ATS (Applicant Tracking System) principles.

# 🚀 Features
1. 📝 Upload your resume (PDF format)

2. 📄 Paste the job description

3. 🤖 Get AI-driven feedback on:

      Resume strengths and weaknesses

      Percentage match with the job description

      Missing keywords

4. 🔐 Uses Gemini AI via Google Generative AI API

# 🛠️ Tech Stack
1. Frontend & Backend: Streamlit

2. AI Model: Gemini 1.5 Pro

3. PDF Processing: pdf2image, Pillow

4. Environment Management: python-dotenv

# 📸 Screenshots
![Image](https://github.com/user-attachments/assets/6b84cfed-a82a-4b40-8ed2-d00ca0885b0b)

![Image](https://github.com/user-attachments/assets/d89d7910-e07e-4853-839f-faaf96949120)

![Image](https://github.com/user-attachments/assets/443349e2-46fe-4a9c-98b8-c4a0cfb43f48)

# 🧠 How It Works
- The user uploads a resume (in PDF format) and provides a job description.

- The app uses pdf2image and Pillow to convert the resume to an image format that can be passed to the Gemini model.

- Gemini generates a text-based evaluation or a percentage match based on provided prompts.

- The response is shown directly in the Streamlit interface.

# 🙌 Acknowledgements
- Google Generative AI (Gemini)

- Streamlit Community

- OpenAI for inspiration


