## **📌 Project Overview**

This project is a **vanilla JavaScript-based self-driving car simulator** featuring AI-controlled cars that use **Neural Networks and Sensors** to navigate roads and avoid traffic. The AI improves over time by learning from past experiences.

📽️ Demo
Added a outputvideo.mp4 in the repo itself.

🚗 **Key Features:**

- 🧠 **AI-Powered Self-Driving Car** using a simple **Neural Network**.
- 🎮 **Manual Mode** (Arrow Keys) for direct user control.
- 🚥 **Traffic Cars** that move dynamically like real-world traffic.
- 🚗 **Sensor-based Collision Detection** for AI learning.
- 📊 **Real-Time Neural Network Visualization**.
- 💾 **Local Storage for AI Learning Progress**.

---

## **🛠️ Technologies Used**

| **Technology**                              | **Purpose**                                |
| ------------------------------------------- | ------------------------------------------ |
| **JavaScript (Vanilla)**                    | Core logic for AI & simulation             |
| **HTML5 Canvas**                            | Graphics rendering for the road, cars & UI |
| **Neural Networks (Custom Implementation)** | AI decision-making for self-driving        |
| **Local Storage API**                       | Saving best-trained AI models              |

---

## **📜 Installation & Usage**

### **🔹 Step 1: Clone the Repository**

`git clone https://github.com/bellapukondaveerendra/self-driving-car-phase1.git
cd self-driving-car-phase1`

### **🔹 Step 2: Open in Browser**

Simply open `index.html` in your preferred web browser. No setup is required.

---

## **🎮 Controls**

- **🚗 Self-Driving Mode (AI-Controlled)** -- The car moves and learns automatically.
- **🎮 Manual Mode (Keyboard Controls)**:
  - `⬆️` **Up Arrow** → Accelerate
  - `⬇️` **Down Arrow** → Reverse
  - `⬅️` **Left Arrow** → Turn Left
  - `➡️` **Right Arrow** → Turn Right
- **💾 Save AI Model** → Click Save Button (💾) to store the best-trained AI.
- **🗑️ Reset AI Learning** → Click Discard Button (🗑️).

---

## **🛠️ How the AI Works**

### **🚗 1. Sensors:**

- The car is equipped with **5 sensor rays**.
- Each ray detects the distance from the **road borders & traffic cars**.

### **🧠 2. Neural Network:**

- The neural network takes **sensor data as input**.
- It decides whether the car should move **forward, left, right, or reverse**.

### **📈 3. AI Learning:**

- The AI improves over time by mutating the best-performing car's **Neural Network**.
- The **best AI model is saved in Local Storage**, allowing continued learning.

---

## **🚀 Future Enhancements**

🚧 **Planned Features:**

- ✅ **Dynamically Generated Traffic** _(Cars continuously spawn & disappear)_
- 🚥 **Traffic Lights & Stop Signs Detection**
- 🏙 **Real-World City Environment**
- 🏆 **AI Fitness Score Optimization**
- 📉 **Graph-based AI Training Analysis**
- 🔥 **Reinforcement Learning (Better AI Decision Making)**

## **👨‍💻 Author**

👤 **Veerendra Bellapukonda**\
🔗 [GitHub](https://github.com/bellapukondaveerendra) | 🔗 [LinkedIn](https://linkedin.com/in/veerendra-bellapukonda-3a1245235)

💡 _Feel free to contribute! Fork the project & submit a pull request!_
