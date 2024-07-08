# app.py
from flask import Flask, request, jsonify, redirect, url_for

app = Flask(__name__)

# Hardcoded user data for demonstration purposes
users = {
    "user1": "password123",
    "user2": "mypassword"
}

@app.route('/login', methods=['POST'])
def login():
    data = request.json
    username = data.get('username')
    password = data.get('password')

    if username in users and users[username] == password:
        return jsonify(success=True)
    else:
        return jsonify(success=False)

@app.route('/protected')
def protected():
    # In a real application, you would use session/cookie to check user authentication
    return "This is a protected page"

if __name__ == '__main__':
    app.run(debug=True)
