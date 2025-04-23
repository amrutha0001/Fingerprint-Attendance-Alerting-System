# 🔐 Fingerprint Attendance & Alerting System  
An **automated biometric attendance solution** built with **Arduino** and **Raspberry Pi**, designed to eliminate proxy attendance, streamline monitoring, and provide real-time alerts via email and Telegram.

📽️ **Presentation**: [Click to View PPT](https://1drv.ms/p/c/bace7122f432be30/EbbWgGuj3ltOkJ6DFetm7kEBJoC7y5uRVqZMo5-WWWShuA?e=8TLwdP)

---

## 🚀 Key Features

- 🔒 **Biometric Authentication**: Ensures 100% genuine attendance through fingerprint recognition.
- 📧 **Email Alerts**: Automatically notifies students falling below the 80% attendance threshold.
- 💬 **Telegram Bot Integration**: Allows students and admins to check attendance on demand.
- ⚡ **Administrative Efficiency**: Reduces manual tracking and workload by up to 70%.
- 📊 **Reliable Data Processing**: Raspberry Pi runs a secure, Linux-based environment for robust performance.

---

## 🔧 Hardware Components

| Component             | Role                                |
|-----------------------|-------------------------------------|
| **Arduino Uno**       | Interfaces with fingerprint sensor  |
| **Raspberry Pi 3B+**  | Acts as the central processing unit |
| **R305 Fingerprint Sensor** | Performs biometric scanning      |
| **5" Touch Display**  | Provides interactive UI             |
| **Power Bank**        | Supplies portable power             |

---

## 💻 Software Stack

- **Python** – Core application logic and bot communication  
- **Linux Shell Scripting** – Background task automation  
- **Yagmail** – Automated email notifications  
- **Telebot API** – Telegram bot integration  
- **Adafruit Fingerprint Library** – Handles fingerprint sensor operations  

---

<!--
## 🛠️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/Fingerprint-Attendance-System.git
cd Fingerprint-Attendance-System

# Install Python dependencies
pip install -r requirements.txt

# Configure system settings
cp config.example.py config.py
```
-->

## ▶️ Usage Guide

### 1. **Enroll Fingerprints**
Use the fingerprint enrollment script to register new students using the connected fingerprint sensor.

### 2. **Run the Attendance System**
```bash
python start.py
```

### 3. **Access Attendance Data**

- 📧 **Email Alerts**:  
  Students who fall below 80% attendance automatically receive an email notification.

- 💬 **Telegram Bot Commands**:  
  Stay updated via the Telegram bot:
  - /start – Initiates interaction with the bot  
  - /attendance – Shows your current attendance status

---

## 📘 Learning Outcomes

- 🧠 Learn to integrate biometric authentication with embedded systems
- 📡 Build real-time alert systems using Python and cloud-based APIs
- 🤖 Deploy IoT applications on Linux-based Raspberry Pi environments
- ⚙️ Automate processes and develop interactive bots for user communication

