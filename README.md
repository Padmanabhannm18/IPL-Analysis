# **🏏 IPL Match Simulator**  

### **🔹 Overview**  
This **IPL Match Simulator** is a **real-time cricket match visualization** tool built using **Streamlit & Pandas**. It simulates live cricket matches using **ball-by-ball IPL data (2008-2020)** and provides:  

✅ **Ball-by-ball updates** with extras & wickets  
✅ **Live scoreboard updates** after every ball  
✅ **Detailed scorecard** after each innings  
✅ **Final match summary** with the winning team  

---

## **📂 Project Structure**  

```
📦 IPL Match Simulator
├── 📁 data
│   ├── IPL Matches 2008-2020.csv
│   ├── IPL Ball-by-Ball 2008-2020.csv
├── 📁 models
│   ├── win_predictor.pkl
├── app.py
├── win_predictor.py
├── visualizer.py
├── README.md
├── requirements.txt
```

### **📝 Files Explanation**  
- **`app.py`** → Main Streamlit app for live match simulation  
- **`win_predictor.py`** → Predicts match winner based on historical data  
- **`visualizer.py`** → Generates match insights & visualizations  
- **`data/`** → IPL datasets  
- **`models/`** → Pre-trained ML models for predictions  

---

## **🚀 Installation & Setup**  

### **🔹 Step 1: Clone the Repository**
```bash
git clone https://github.com/Padmanabhannm18/IPL-Match-Simulator.git
cd IPL-Match-Simulator
```

### **🔹 Step 2: Install Dependencies**  
Create a virtual environment & install required libraries:  
```bash
pip install -r requirements.txt
```

### **🔹 Step 3: Run the Application**  
```bash
streamlit run app.py
```

---

## **🎮 Features & Functionality**  

### **🏏 Live Match Simulation**
- Select a match from **2008-2020 IPL data**
- Watch **real-time ball-by-ball updates**  
- Shows **extras like wides, no-balls, leg-byes**  
- Updates **batsman’s individual score** live  

### **📊 Scorecard & Match Summary**
- **Scorecard at the end of each innings**
- Displays **batsmen’s total runs & bowler’s wickets**
- **Final match summary** with winner announcement  

### **🧠 Machine Learning Predictions**
- **Win Predictor** → Predicts match winner based on teams & venue  

---

## **🛠️ Future Enhancements**
✅ Real-time IPL 2024 match tracking using API  
✅ Add team-wise & player-wise statistics  
✅ Interactive charts for match trends  

---

## **📌 Contributing**
1. **Fork** the repository  
2. **Create a branch** (`feature/new-feature`)  
3. **Commit your changes**  
4. **Push to GitHub** & create a **Pull Request**  

---

## **📜 License**
This project is licensed under the **MIT License**.  

---

## **💬 Need Help?**
Feel free to raise an issue or contact me at **padmanabhannm18@gmail.com**.  
