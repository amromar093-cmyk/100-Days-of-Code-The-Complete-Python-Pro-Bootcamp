Password Generator

A desktop password generator and manager built with Tkinter. Generate strong random passwords with one click and save your website, email, and password entries locally.

Features
Generates a random password made of a shuffled mix of letters, numbers, and symbols
Auto-copies the generated password to the clipboard
Simple form to enter a website and email, paired with the generated (or your own) password
Saves each entry as a new line in data.txt in the format website | email | password
Pre-fills the email field with a default address to speed up repeated entries
Warns you if the website or password field is left empty before saving

Project structure
password-generator/
├── main.py # Entry point - builds the Tkinter GUI and handles generate/save logic
├── logo.png # Padlock logo shown at the top of the window
├── data.txt # Saved entries (website | email | password), one per line
├── requirements.txt
└── README.md

Requirements
Python 3.x with Tk/Tkinter support (ships with most standard Python installs; on Linux you may need sudo apt install python3-tk), plus the pyperclip package.

How to run
pip install -r requirements.txt
python3 main.py

How to use
Enter the website name, then click "Generate Password" to fill in a random password (also copied to your clipboard automatically). Adjust the email if needed, then click "Add" to confirm and append the entry to data.txt.
