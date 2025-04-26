What is the framework used?
Flask is great for simple, quick websites and prototypes.
It's super beginner friendly but also powerful for bigger projects.

How to Run the Project (Step-by-Step)
pip install flask
/project_folder
    app.py
    /templates
        home.html
        about.html
        contact.html
app.py → Main Python file to run the server
/templates → Folder where your HTML files are stored

Run the Flask App
python app.py
python3 app.py
Running on http://127.0.0.1:5000/

Open Your Browser
Go to http://127.0.0.1:5000/
Navigate between Home, About, and Contact pages.


Issue Encounter
Flask not installed error Flask is missing on your computer
solution Install it with pip install flask

Server not restarting when code changes Flask debug mode is OFF
solution Set debug=True in app.run(debug=True) 
if __name__ == '__main__':
    app.run(host='0.0.0.0', port=5000)
    app.run(host='192.168.1.10', port=5000)
