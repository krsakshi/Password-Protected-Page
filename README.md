# Password-Protected-Page
<p> In this project, we created a simple password-protected page using HTML, CSS, JavaScript, and Python (Flask). The goal is to demonstrate how to set up a basic authentication mechanism to restrict access to specific content on a webpage. </p> <h2>Features:</h2> <h3>Login Form (HTML & CSS)</h3> <ul> <li>A clean and responsive login form designed with HTML and CSS.</li> <li>The form includes fields for username and password, along with a submit button.</li> </ul> <h3>Client-Side Validation (JavaScript)</h3> <ul> <li>JavaScript handles the form submission to prevent the default behavior and sends the input data to the server using the Fetch API.</li> <li>If the login credentials are correct, the user is redirected to a protected page.</li> <li>If the credentials are incorrect, an alert is shown to the user.</li> </ul> <h3>Server-Side Authentication (Python & Flask)</h3> <ul> <li>A simple Flask server is set up to handle the login requests.</li> <li>User credentials are hardcoded for demonstration purposes.</li> <li>The server checks the credentials sent from the client and responds with a success or failure message.</li> <li>Upon successful authentication, the user is redirected to a protected page.</li> </ul> <h2>Steps to Run the Application:</h2> <h3>HTML, CSS, and JavaScript Setup:</h3> <ul> <li>Create an HTML file for the login form and include references to the CSS and JavaScript files.</li> <li>Style the form using CSS to make it visually appealing and user-friendly.</li> <li>Write JavaScript code to handle the form submission and communicate with the server.</li> </ul> <h3>Python (Flask) Setup:</h3> <ul> <li>Install Flask using pip (pip install flask).</li> <li>Create a Python script to set up a Flask server.</li> <li>Define routes for handling login requests and serving the protected content.</li> <li>Implement a basic authentication mechanism using hardcoded user data.</li> </ul> <h3>Run the Application:</h3> <ul> <li>Start the Flask server by running the Python script (python app.py).</li> <li>Open a web browser and navigate to http://127.0.0.1:5000/ to access the login form.</li> <li>Enter the credentials to log in and access the protected page.</li> </ul> <h2>Considerations:</h2> <ul> <li>This example uses hardcoded user credentials for simplicity. In a real application, credentials should be securely stored in a database with proper encryption.</li> <li>For enhanced security, consider implementing session management and using HTTPS for secure communication.</li> </ul> <p> This project serves as a foundation for understanding how to create a password-protected page. Additional features like password recovery, account creation, and more can be built upon this base. </p> <p> This project is a great starting point for learning how to implement basic authentication mechanisms in web applications. It combines front-end development (HTML, CSS, JavaScript) with back-end development (Python, Flask) to create a functional and secure login system. </p>
<img src="Login Page.png" alt=" Image ">

<!-- LICENSE -->
## License

Distributed under the MIT License. Click [https://github.com/krsakshi/Calculator/blob/main/LICENSE.md] for more information.
