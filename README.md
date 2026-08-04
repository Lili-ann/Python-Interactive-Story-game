# 👁️ Eye Scare — Interactive Horror Story

A text-based interactive horror story game built entirely on Python, but is now playable in the browser as a web app can click the demo link

You wake up bound and trapped in a dark, decaying room with a mysterious anklet on your leg displaying the number **74** — your health. The house is alive and unforgiving. Every choice you make drains or restores your HP. Reach zero and it's over. There are **5 different endings** to discover depending on the paths you take.

---

### Requirements

- Python 3.8+
- Flask
- Gunicorn (for production)

### Install dependencies

```bash
pip install flask gunicorn
```

### Run in development

```bash
python app.py
```

## 🖥️ Console Version (Original)

The original Python console game is preserved in the `EYE SCARE project/` folder.

```bash
cd 'EYE SCARE project'
python maingame.py
```

Follow the on-screen prompts. Answers are **case sensitive**.

---

## 📁 Project Structure

```
├── app.py                        # Flask backend — game logic, session state, API routes
├── templates/
│   └── index.html                # Single-page frontend (title, game, ending screens)
├── static/
│   ├── style.css                 # Horror theme — fonts, HP bar, animations
│   └── game.js                   # Typewriter engine, HP display, API calls
└── EYE SCARE project/            # Original Python console game (unchanged)
    ├── maingame.py               # Entry point — game loop
    ├── choicesystem.py           # Choice handling and branching logic
    ├── choicedisplay.py          # All story text and display functions
    ├── healthsystem.py           # HP / anklet system
    └── itemsystem.py             # Item and weapon management
```
