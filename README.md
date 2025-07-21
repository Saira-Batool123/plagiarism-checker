Plagiarism Checker
Overview
The Plagiarism Checker is a web-based application designed to help students, educators, and writers ensure the originality of their content by detecting potential plagiarism. Built using HTML, CSS, JavaScript, and Node.js, the tool allows users to input text or upload documents, compare them against a database or online sources, and receive a detailed report with a similarity percentage. Developed by Saira Batool, a student at UET Lahore (Narowal Campus), this project showcases front-end and back-end development skills, focusing on academic integrity and user-friendly design. The application features a clean, responsive interface with a pastel-themed aesthetic, suitable for academic and professional use.
Features

Text Input and File Upload: Users can paste text or upload files (.txt, .docx, .pdf) to check for plagiarism.
Similarity Detection: Compares input text against a local database or online sources, highlighting matching content with source links.
Percentage Report: Displays a plagiarism percentage and detailed report, identifying identical, paraphrased, or similar text.
Exclude Quotes: Option to exclude quoted text from the plagiarism check to focus on original content.
Responsive Design: Fully responsive UI using Tailwind CSS, optimized for desktops, tablets, and mobile devices.
User Authentication: Optional login system for saving scan history, using JWT and bcrypt for secure authentication.
Downloadable Reports: Generate and download plagiarism reports in PDF or HTML format.
Real-Time Feedback: Instant results with highlighted text and source references for easy review.

Technologies Used

HTML5: For structuring the web application.
CSS3 with Tailwind CSS: For styling and responsive design with a pastel-themed, glassmorphism-inspired UI.
JavaScript: For client-side logic, including text processing and result visualization.
Node.js with Express: For backend API to handle file uploads, text comparison, and authentication.
JSON Web Tokens (JWT): For secure user authentication (optional feature).
bcryptjs: For password hashing in the authentication system.
pdfkit: For generating downloadable PDF reports.
Font Awesome: For icons to enhance the user interface.
Local Storage: For temporary storage of scan results and user preferences.
<img width="660" height="524" alt="image" src="https://github.com/user-attachments/assets/233a1884-6a08-42f0-bea6-f05e9e7c4e0b" />
<img width="893" height="438" alt="image" src="https://github.com/user-attachments/assets/290e3db3-ad7a-4a92-abf5-cc7b2b28f578" />


Installation
To run the Plagiarism Checker locally, follow these steps:

Clone or Download the Repository:
git clone https://github.com/Saira-Batool123/plagiarism-checker.git

Alternatively, download the project as a ZIP file from GitHub and extract it.

Navigate to the Project Directory:
cd plagiarism-checker


Install Backend Dependencies:

Ensure Node.js is installed (download from nodejs.org).
Install dependencies listed in package.json:npm install

This installs express, jsonwebtoken, bcryptjs, pdfkit, and body-parser.


Run the Backend Server:

Start the Node.js server:node server.js

The server will run on http://localhost:3000 (or another port if specified).


Run the Frontend:

Open index.html in a web browser (e.g., Chrome, Firefox) using a local server:python -m http.server 8000

Access the application at http://localhost:8000.


Dependencies:

Ensure an internet connection to load external libraries via CDN:
Tailwind CSS: https://cdn.tailwindcss.com
Font Awesome: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css


Node.js dependencies are managed via npm install.



Usage

Open the Application:

Launch the Plagiarism Checker in a web browser via http://localhost:8000.


User Authentication (Optional):

Register or log in to save scan history (if enabled).
Use the guest mode to check text without logging in.


Check for Plagiarism:

Text Input: Paste your text into the provided text box.
File Upload: Upload a file (.txt, .docx, .pdf) using the "Choose File" button.
Options: Check "Exclude Quotes" to skip quoted text in the scan.
Click "Check Plagiarism" to start the scan.


Review Results:

View the plagiarism percentage and a detailed report highlighting matching text.
Click on source links to see where similar content was found.
Download the report as a PDF or HTML file using the "Download Report" button.


Manage Scan History:

If logged in, view past scans in the "History" section.
Clear history or individual scans as needed.



Project Structure
plagiarism-checker/
├── .ipynb_checkpoints        # Main HTML file for the frontend
├── doc1.txt        # Custom CSS (supplements Tailwind CSS)
├── doc2.txt         # JavaScript for client-side logic and text processing
├── doc3.txt        # Node.js backend for API and authentication
├── report.txt      # Node.js dependencies and scripts
├── Untitled          # Folder for assets (e.g., screenshots)
└── README.md         # This file



Fork the repository.
Create a new branch: git checkout -b feature/your-feature-name.
Make your changes and commit: git commit -m "Add your feature description".
Push to your branch: git push origin feature/your-feature-name.
Submit a pull request on GitHub.


For any queries or suggestions, reach out to:

Saira Batool
Email: batoolsaira957@gmail.com
GitHub: Saira-Batool123


Created by Saira Batool, UET Lahore (Narowal Campus), 2025
