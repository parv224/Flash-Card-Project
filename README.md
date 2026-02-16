# Flash Card Project (Tkinter + Python)

A simple **Flash Card Learning Application** built using **Python (Tkinter, Pandas)** to help users memorize vocabulary efficiently.  
The app displays a French word, waits for a few seconds, then flips the card to show the English meaning. Users can mark words as **known** or **unknown**, and the app automatically tracks learning progress.

---

# Features

- Random French word display  
- Automatic card flip after 3 seconds  
- Mark words as **Known** or **Unknown**  
- Saves remaining learning words automatically  
- Progress tracking using CSV files  
- Simple and clean GUI using Tkinter  

---

# Project Structure

flash-card-project/
│
├── data/
│ ├── french_words.csv
│ └── words_to_learn.csv
│
├── images/
│ ├── card_front.png
│ ├── card_back.png
│ ├── right.png
│ └── wrong.png
│
├── main.py
└── README.md


---

# Requirements

Install required library:

```bash
pip install pandas
How It Works
The app loads vocabulary from french_words.csv

When a user marks a word as known, it is removed from the learning list

Remaining words are saved in words_to_learn.csv

On the next run, the app continues from where the user left off

Technologies Used
Python

Tkinter (GUI)

Pandas (Data handling)

CSV storage for persistence

Future Improvements
Add pronunciation audio

Add multiple language support

Add progress statistics dashboard

Dark mode UI

Author
Parv Prajapati
Computer Engineering Student | Python Developer
