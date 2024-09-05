📄 Automatic Resume Builder

This Python script helps users create professional resumes by collecting their personal information, educational qualifications, work experience, and skills, and then generates a formatted PDF resume. It uses the FPDF library to export the information into a structured document.

🚀 Features

Collects user details such as:
Full name
Email
Phone number
Educational qualifications
Work experience
Skills
Automatically generates a PDF resume.
Randomly assigns a unique file name to each resume.
Displays the time of completion when the resume is generated.
🛠️ Requirements

Python 3.x
FPDF Library
To install the FPDF library, use:

bash
Copy code
pip install fpdf
📂 Project Structure

bash
Copy code
📦 ResumeBuilder
 ┣ 📜 resume_builder.py     # The main script for generating resumes
 ┗ 📜 README.md             # Project documentation
🎯 How It Works

Run the script.
Input your personal details when prompted:
Full name
Email
Phone number
School, degree, and year of education
Company name, position, and work years
Skills (separated by commas)
Enter a custom name for your PDF file.
A resume is generated and saved with a random unique number appended to the file name.
📄 Example Output (PDF)

The script generates a PDF with the following sections:

Personal Information
Name, Email, Phone
Educational Qualifications
School, Degree
Work Experience
Company, Position, Work Year
Skills
List of skills
💻 Usage

Run the script:

bash
Copy code
python resume_builder.py
You will be prompted to enter details, and a PDF file will be created in the current directory.

🛡️ License

This project is licensed under the MIT License. Feel free to modify and distribute it.
