<h1>Campus Compass 🧭</h1>
    <p><strong>Campus Compass</strong> is a lightweight Python web application designed to provide campus-related utilities, APIs, or navigation-based services. 
    It is structured for easy deployment, scalability, and containerization using Docker.</p>

   <h2>🚀 Features</h2>
    <ul>
        <li>Clean and simple Flask backend structure</li>
        <li>API routes managed through <code>app.py</code></li>
        <li>Docker-ready configuration</li>
        <li>Easy to extend and customize</li>
    </ul>

  <h2>🧱 Tech Stack</h2>
    <table>
        <tr>
            <th>Technology</th>
            <th>Purpose</th>
        </tr>
        <tr>
            <td>Python</td>
            <td>Core backend language</td>
        </tr>
        <tr>
            <td>Flask</td>
            <td>Web framework</td>
        </tr>
        <tr>
            <td>Docker</td>
            <td>Containerization</td>
        </tr>
        <tr>
            <td>GitHub Actions</td>
            <td>CI/CD workflows</td>
        </tr>
    </table>

   <h2>📁 Project Structure</h2>

   <pre>
campus-compass/
│
├── .github/workflows/
├── Dockerfile
├── app.py
├── requirements.txt
└── README.md
    </pre>

   <h2>📌 Getting Started</h2>

  <h3>Prerequisites</h3>
    <ul>
        <li>Python 3.8+</li>
        <li>pip</li>
        <li>Docker (optional)</li>
    </ul>

  <h3>Clone the Repository</h3>
    <pre>
git clone https://github.com/javintrivedi/campus-compass.git
cd campus-compass
    </pre>

  <h3>Install Dependencies</h3>
    <pre>
pip install -r requirements.txt
    </pre>

  <h3>Run the Application</h3>
    <pre>
python app.py
    </pre>

  <p>The application will typically run at:</p>
    <code>http://127.0.0.1:5000</code>

   <h2>🐳 Running with Docker</h2>

   <pre>
docker build -t campus-compass .
docker run -p 5000:5000 campus-compass
    </pre>

   <p>Access the app at:</p>
    <code>http://localhost:5000</code>

   <h2>🛠️ Future Enhancements</h2>
    <ul>
        <li>Interactive campus map interface</li>
        <li>Database integration</li>
        <li>User authentication</li>
        <li>Frontend integration (React/Vue)</li>
    </ul>

  <h2>🤝 Contributing</h2>
    <p>Contributions are welcome!</p>
    <ol>
        <li>Fork the repository</li>
        <li>Create a new branch</li>
        <li>Commit your changes</li>
        <li>Push and create a pull request</li>
    </ol>

   <h2>📄 License</h2>
    <p>No license specified yet. Consider adding an MIT or Apache 2.0 license for open-source distribution.</p>

  <hr>
    <p><em>Made by Javin Trivedi and Sania Tanweer</em></p>

</body>
</html>
