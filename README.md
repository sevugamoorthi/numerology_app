# Baaloo Numerology App 🧮

A **Kivy-based GUI application** that provides numerological insights by analyzing names and dates of birth (DOB).  
Users can calculate numerological values based on ancient number principles and save results to local text files.

---

## 📜 Features
- Interactive GUI built with **Kivy**.
- Multiple screens managed with `ScreenManager`.
- Allows input of **Name**, **DOB**, or both for analysis.
- Converts letters into numerological values using predefined mappings.
- Displays numerological calculations and saves them to a specified file path.
- Includes an intro video and image-based splash screen.

---

## 🧰 Tech Stack
- **Python 3.8+**
- **Kivy** for UI/UX
- **Kivy ScreenManager** for navigation
- **Kivy Builder** for dynamic layout loading

---

## 📁 Project Structure
```
📦 Baaloo_Numerology_App
 ┣ 📜 main.py              # Main application code
 ┣ 📜 Icon.ico             # App icon
 ┣ 📜 Baaloo.png           # Intro image
 ┣ 📜 lv_0_20240114201246.mp4  # Intro video
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sevugamoorthi/numerology_app.git
   cd numerology_app/
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python main.py
   ```

---

## 💡 Usage Instructions

1. Launch the app — the intro video will play first.
2. Tap anywhere to skip the intro.
3. Choose one of the following options:
   - **Name**: Analyze numerology based on name.
   - **DOB**: Analyze numerology based on date of birth.
   - **Name & DOB**: Combine both analyses.
4. Enter inputs and specify the file path for saving results.
5. Click **Save** to generate your numerology report.

---

## 🧮 Numerology Logic
Each alphabet is mapped to a specific number:
```
A=1, B=2, C=3, D=4, E=5, F=8, G=3, H=5, I=1,
J=1, K=2, L=3, M=4, N=5, O=7, P=8, Q=5, R=2,
S=3, T=4, U=6, V=6, W=6, X=5, Y=1, Z=5
```
The program computes sums and reduces them to single digits to reveal hidden numerological meanings.

---

## 📂 Output Example
Example saved file content:
```
Your name is: Baaloo
Number: 211355
Total: 17
Hebrew: 8
Your DOB is: 24071998
Total: 40
Hebrew: 4
```

---

## 🧑‍💻 Author
**Baaloo G. Iyer**  
Expert in numerology and pattern analysis.  
📧 Contact: sevugamoorthi738@gmail.com

---