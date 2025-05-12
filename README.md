# 🦠 Virus-Ultimate_Python

Welcome to **Virus-Ultimate_Python** — a collection of Python-based prank scripts meant for **educational and entertainment** purposes only. These notebooks are designed to surprise, confuse, and amuse — while helping you learn about Python’s interaction with systems.

> ⚠️ **DISCLAIMER:** This repository is for **educational use only**. Do not run these notebooks on any system you do not own or without full permission. Always test in a sandboxed or virtual environment. The code is meant for learning, not for harm.

---

## 📂 Repository Contents

Here’s what’s inside the repo:

### 🔁 Prank Notebooks Series
Each of the following `.ipynb` notebooks has a different kind of harmless "virus" prank:

1. **`run this code if you are not gay it's just a game chill 1.ipynb`**  
   - This script is engineered to flood your default web browser with an extremely high-frequency bursts of URLs. Specifically, it attempts to open website links at an insanely rapid interval of about 0.000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001 seconds between each tab. That's so fast it practically means "open all at once".

   - Once executed, you will likely experience an instant and overwhelming flood of browser windows/tabs opening non-stop. Depending on your system's specs, browser settings, and internet connection, this may cause your browser to freeze, your RAM usage to spike, or your system to become momentarily unresponsive.
   - ⏲️ To CONTROL the SPEED at which each link opens, look for the line that contains time.sleep(...). The number inside sleep() determines the delay in seconds. For example: time.sleep(1) → opens a new link every 1 second (slow & safe) OR time.sleep(0.1) → opens a new link every 100ms (moderate speed) OR time.sleep(0.0001) → opens links nearly instantly (chaotic)
   - 🌐 To CHANGE THE WEBSITES being opened: Locate the lines where webbrowser.open() is called. You’ll see URLs in quotation marks like: webbrowser.open("https://example.com"). Replace these with any URLs of your choice. Make it fun by inserting meme links, Rickrolls, or fake search results. For example: webbrowser.open("https://www.youtube.com/watch?v=dQw4w9WgXcQ")

2. **`run this code if you are not gay it's just a game chill 2.ipynb`**  
   - Opens random websites endlessly in the browser.  
   - Uses `webbrowser.open()` in a loop.

3. **`run this code if you are not gay it's just a game chill 3.ipynb`**  
   - Auto-types random characters using `pyautogui`.  
   - Simulates keyboard chaos.

4. **`run this code if you are not gay it's just a game chill 4.ipynb`**  
   - Moves mouse cursor randomly.  
   - Classic “ghost in the machine” effect.

5. **`run this code if you are not gay it's just a game chill 5.ipynb`**  
   - Flashes the screen colors using GUI libraries.  
   - Visual overload.

6. **`run this code if you are not gay it's just a game chill 6.ipynb`**  
   - Triggers random system sounds continuously.  
   - Fun, chaotic audio prank.

7. **`run this code if you are not gay it's just a game chill 7.ipynb`**  
   - Types memes or emojis repeatedly.  
   - Spam-troll for messages.

8. **`run this code if you are not gay it's just a game chill 8.ipynb`**  
   - Continuously creates and opens `.txt` files with funny names.  
   - Mild file spam.

9. **`run this code if you are not gay it's just a game chill 9.ipynb`**  
   - Makes fake error messages.  
   - Harmless system dialog trolls.

10. **`run this code if you are not gay it's just a game chill 10.ipynb`**  
    - System beeps and popups on repeat.  
    - Combines multiple prank types.

11. **`run this code if you are not gay it's just a game chill 11.ipynb`**  
    - Opens a camera feed window with effects (if webcam access).  
    - Interactive prank.

12. **`run this code if you are not gay it's just a game chill 12.ipynb`**  
    - Reverses mouse direction using software logic.  
    - Annoying but funny.

13. **`run this code if you are not gay it's just a game chill 13.ipynb`**  
    - Changes screen brightness or color filters rapidly.  
    - Use with caution.

14. **`run this code if you are not gay it's just a game chill 14.ipynb`**  
    - Auto-clicker chaos mode.  
    - Clicks random points on the screen.

15. **`run this code if you are not gay it's just a game chill 15.ipynb`**  
    - Spawns emoji storms in text editors.  
    - Visual overload via typing.

16. **`run this code if you are not gay it's just a game chill 16.ipynb`**  
    - Slowly changes desktop wallpaper (Windows only).  
    - Persistent visual prank.

17. **`run this code if you are not gay it's just a game chill 17.ipynb`**  
    - Hijacks taskbar with dummy alerts.  
    - Simulates system warnings.

18. **`run this code if you are not gay it's just a game chill 18.ipynb`**  
    - Prints endless ASCII art in terminals.  
    - Useless but hypnotic.

19. **`run this code if you are not gay it's just a game chill 19.ipynb`**  
    - All-in-one combo prank (mild version).  
    - Samples multiple effects from earlier notebooks.

---

### 🔬 Other Files

- **`Counter Code.ipynb`**  
  A countdown or count-up script for testing loops and UI elements. Useful for delaying or setting up effects.

- **`Test Beta Lab.ipynb`**  
  Experimental notebook used for testing new prank ideas and proof-of-concepts.

- **`run this code if you are not gay it's just a game chill 10.workflow.zip`**  
  A macOS Automator workflow version of Notebook 10, allowing integration into system-level automation.

---

## 🚀 Getting Started

### Requirements
Install required Python modules:
```bash
pip install pyautogui tkinter playsound opencv-python pillow
