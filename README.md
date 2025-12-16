 🔐 GuardX — AI-powered Intrusion Detection System (IDS) Prototype
 
 🌟 Project Overview

During the hackathon, our team developed an **AI-powered Intrusion Detection System (IDS)** prototype to enhance cybersecurity. The system is designed to **analyze URLs in real-time** and detect potential threats before they affect users.  

**Key Features:**

- ✅ Identify if a URL is **safe or a potential threat**  
- ✅ Determine **risk levels**: Low, Medium, High, Critical  
- ✅ Classify **threat types**: Malware, Phishing, Defacement, Benign  
- ✅ Extract **key details**: IP Address & Hosting Country  
- ✅ Show **detection confidence**  
- ✅ Check if the URL is **blacklisted**  
- ✅ Generate **bar graph visualizations** for better analysis  


 🔍 Dataset Used

We trained and evaluated our model using a **malicious URL detection dataset** containing:  

- Phishing URLs  
- Defacement URLs  
- Benign URLs  
- Associated metadata: IP addresses, hosting countries, blacklist status  

This dataset enabled our AI system to **classify and assess threats effectively**.



💻 Technology Stack

| Component | Description |
|-----------|-------------|
| **Python** | Backend logic and AI model |
| **Streamlit** | User-friendly web interface |
| **Machine Learning** | Model for threat detection & classification |
| **Data Visualization** | Bar graphs for risk and confidence levels |

🚀 Future Enhancements

To further isolate threats, we plan to integrate **Docker-based virtualization**:  

- Malicious URLs will launch in a **secure virtual environment** instead of the main system  
- Environment automatically shuts down after use  
- Ensures **complete system protection**  

This will make GuardX a **proactive, AI-driven cybersecurity solution**.



## 📜 License

Educational/demo use. Built for hackathon prototype purposes only.  
© 2025 Team GuardX
