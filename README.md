# 🚨 Intruder Alarm System with Edge AI and Twilio

A Raspberry Pi-based security system that uses a PIR sensor for motion detection, a USB camera for visual verification, and an AI model to detect intruders. When an intruder is confirmed, an alert is sent via Twilio SMS.

---

## 🧠 Features

- 🔍 PIR sensor triggers image capture
- 🧠 USB camera image is classified using Edge AI (person/no person)
- 📲 If a person is detected → Twilio sends an SMS alert
- 📷 Optional: save image locally or to cloud for review

---

## 🛠️ Hardware

- Raspberry Pi (3B+ or 4 recommended)
- USB camera
- PIR Motion Sensor
- Internet connection (Wi-Fi or Ethernet)

---

## 🧰 Software

- Python 3.x
- Edge Impulse SDK
- OpenCV
- Twilio API

---

## 📁 Folder Structure

intruder-alarm-ai-system/
├── main.py
├── requirements.txt
├── model/ # AI model files (.eim)
├── alert_images/ # Saved images of intrusions
├── README.md


---

## 🚀 To Run

```
pip install -r requirements.txt
python3 main.py
```
🔐 Twilio Setup
Create a Twilio account

Get your:

Account SID

Auth Token

Phone number

Add them to a .env file (not pushed to GitHub)

🤖 Future Enhancements
Video stream on alert

Telegram or email alerts

Object/person tracking

Time-based alert zones

👨‍💻 Author
📫 akpsalmol@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/olalekan-samuel-akadiri-9b43a91b3/  
🌍 GitHub: https://github.com/Psalmol/

---
