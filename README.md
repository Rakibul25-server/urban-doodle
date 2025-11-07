from flask import Flask
app = Flask(__name__)

@app.route("/")
def home():
    return "Hello ভাইজান! My first free server is live!"

if __name__ == "__main__":
    app.run()
