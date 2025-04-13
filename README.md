# VisionRaise

An AI-powered, fully autonomous **Poker Game Agent** that plays online poker just like a human — by seeing, understanding, and acting — with **no API access**, just real-time screen interaction and intelligent decision-making.

---

## 🚀 Overview

This project demonstrates how to combine **Computer Vision**, **Automation**, and **Probability Logic** to build a poker-playing agent that:

- Logs into an online poker platform
- Reads cards from the screen using OCR
- Calculates winning probabilities
- Makes strategic betting decisions (Fold, x2, x3, All-In)
- Interacts with the UI using mouse automation
- Plays poker in real time — with zero API access

---

## 🔍 Key Features

- 🎯 **Real-Time Game Interaction**  
  Navigates the site, joins tables, and interacts like a real player.

- 🧠 **Strategic Decision Making**  
  Evaluates hand strength using basic probability rules.

- 🖥️ **Visual Understanding**  
  Extracts game state using OCR and pixel-level image processing.

- 📈 **Win Probability Estimation**  
  Uses card frequency and hand ranking logic to determine betting strategy.

- 🖱 **UI Automation**  
  Uses PyAutoGUI to simulate human-like clicks and interactions.

---

## 🛠 Tech Stack

| Component            | Tool/Library         |
|----------------------|----------------------|
| OCR & Text Detection | [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) |
| Image Processing     | [OpenCV](https://opencv.org/), [PIL](https://pillow.readthedocs.io/) |
| Browser Automation   | [DrissionPage](https://github.com/ClericPy/DrissionPage) |
| GUI Control          | [PyAutoGUI](https://pyautogui.readthedocs.io/) |
| Logic & Math         | NumPy, Python Counter |
| Screen Capture       | ImageGrab |

---

## 🧠 How It Works

1. **Login Automation**: Launches browser, enters credentials, and navigates to the poker table  
2. **Screen Parsing**: Captures defined screen regions to detect cards  
3. **Card Detection**: Uses OCR to read player and community cards  
4. **Probability Estimation**: Computes rough win probability based on hand strength  
5. **Decision Logic**: Chooses an action (Fold, x2, x3, All-In)  
6. **Click Execution**: Automates mouse click for selected betting button  
7. **Looping Logic**: Waits for next turn and repeats the process

---

## 📸 Screenshots (Coming Soon)
Add visual examples of:
- OCR detection of cards
- Detected screen regions
- Bot decision-making log

---

## 🚧 Future Enhancements

- 🔁 Monte Carlo simulations for advanced hand strength calculation  
- 📚 Store and learn from past game history using a vector database  
- 🧠 Integrate reinforcement learning to adapt strategies  
- 🤖 Add LLM (e.g., GPT) for decision explainability  
- 🌍 Make it compatible with multiple poker platforms  

---

## 🤝 Collaboration

If you're building in the space of **AI**, **automation**, or **real-time game agents**, feel free to open issues, share feedback, or collaborate!

---

## 📄 License

This project is open-source under the MIT License.

---

## 📬 Contact

📧 Email: ismailsarfraz9345@gmail.com  
💼 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/ismail-sarfraz/)  

---

## ⭐️ Show Your Support

If you found this project interesting or helpful, please consider giving it a ⭐️ and sharing it with others in the AI and gaming automation space!

