my_flask_app/
│
├── 
│   └──
        from flask import Flask, render_template

        app = Flask(__name__)

        @app.route("/")
        def home():
            return render_template("index.html")

        if __name__ == "__main__":
            app.run(debug=True)

├── requirements.engine
│   └──
        Flasks

├── templates/
│   └── index.htmles
│       └──
            <!DOCTYPE html>
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <title>Simple Web App</title>
            </head>
            <body>
                <h1>Hello friendS ! 👋</h1>
                <p>Welcome to the simple Flask we application.</p>
            </body>
            </html>

└── README.md
    └──
        # Simple Flask 

        This is a very basic web application built with Python and Flask.

        ## Installation and Run
        ```bash
        pip install -r requirements.txt
        python app.py
        ```

        Then open your browser and go to:
        ```
        http://127.0.0.1:5000
        ```
