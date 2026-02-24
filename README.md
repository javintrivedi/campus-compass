Campus Compass 🧭

Campus Compass is a lightweight Python web app designed to serve as a backend API or navigation-related service for campus utilities — such as finding locations, managing campus data, or providing a simple interface to campus resources.

🚀 Features

🔹 Simple and clean Python/Flask structure

🔹 API routes powered by app.py

🔹 Easily containerizable with Docker

🔹 Lightweight and easy to extend

🧱 Tech Stack
Component	Purpose
🐍 Python	Core backend language
🧠 Flask	Web framework for API/UI
📦 requirements.txt	Project dependencies
🐳 Docker	Containerization (optional)
📁 Repository Structure
📦 campus-compass
├── .github/workflows/     # CI/CD workflows
├── Dockerfile             # Docker container config
├── app.py                 # Main Flask application
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
📌 Getting Started
🧩 Prerequisites

Make sure you have installed:

Python 3.8+

pip (Python package manager)

(Optional) Docker

🛠️ Local Development

Clone the repository:

git clone https://github.com/javintrivedi/campus-compass.git
cd campus-compass

Install dependencies:

pip install -r requirements.txt

Run the app:

python app.py

The application should now be running locally (e.g., on http://127.0.0.1:5000, if using Flask defaults).

🐳 Using Docker (Optional)

Build the Docker image:

docker build -t campus-compass .

Run the container:

docker run -p 5000:5000 campus-compass

Access the app at http://localhost:5000.

📦 Dependencies

All required Python packages are listed in requirements.txt.

Example:

Flask==<version>
...

(Edit this file to include actual dependency versions if missing.)

📝 Contributing

Contributions are welcome! 🎉
To contribute:

Fork this repository

Create a new branch (git checkout -b feature/YourFeature)

Commit your changes

Push to your fork

Open a pull request

🛠️ Future Improvements

Here are some ideas you might want to add:

🔹 Campus map UI with interactive navigation

🔹 Integration with React/Vue frontend

🔹 Database for user data and location metadata

🔹 Authentication / user accounts

📄 License

This project doesn’t currently specify a license.
Consider adding an open source license like MIT / Apache 2.0 for community use.
