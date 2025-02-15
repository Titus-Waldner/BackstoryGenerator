Randomized Character Backstory Generator
Overview

This project is a randomized backstory generator that creates unique character backgrounds using Tkinter for a GUI interface. It constructs dynamic and diverse character stories by pulling from pre-defined text files, ensuring endless variations.
Features

    Randomized character details including names, places, jobs, weaknesses, aspirations, and personalities.
    Procedural story generation using structured templates for coherent yet randomized backstories.
    Graphical User Interface (GUI) built with Tkinter, featuring a styled text box and buttons.
    Dynamic text file integration, allowing easy customization by modifying input files.

How It Works

The program loads pre-written lists of:

    Names
    Adjectives
    Places
    Nouns
    Verbs
    Jobs
    Weaknesses
    Future aspirations
    Love interests
    Significant life events
    Early life experiences
    Personalities
    Likes & dislikes

Each backstory is generated randomly by selecting values from these lists and inserting them into predefined sentence structures. The result is a unique, readable story every time.
Installation
1. Install Python (if not already installed)

Ensure you have Python 3 installed. You can download it from: Python Official Website
2. Install Required Libraries

Run the following command:

pip install tkinter

(Tkinter is usually included with Python, but install it if missing.)
Usage
Running the Program

    Place the script in a directory containing a subfolder named inputs/.
    Ensure text files (e.g., name.txt, adjective.txt, etc.) exist inside inputs/.
    Run the script:

python backstory_generator.py

A window will appear with a text box and a "Generate new backstory" button.
Clicking the button generates a new backstory and displays it in the text box.
