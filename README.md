# Fingerprint-Attendance-Alerting-System with Arduino & Raspberry Pi
A secure, automated attendance system that eliminates proxy attendance using biometric authentication and real-time notifications.

PPT link for the project : https://1drv.ms/p/c/bace7122f432be30/EbbWgGuj3ltOkJ6DFetm7kEBJoC7y5uRVqZMo5-WWWShuA?e=8TLwdP


## Key Features
- 🔒 **Biometric Security**: Fingerprint authentication ensures 100% genuine attendance records
- 📧 **Automated Alerts**: Email notifications for students below 80% attendance
- 🤖 **Telegram Bot**: Real-time attendance queries via Telegram
- ⚡ **Efficiency**: Reduced administrative workload by 70%
- 📊 **Data Accuracy**: Linux-based processing ensures reliable record-keeping

## Hardware Components
| Component | Purpose |
|-----------|---------|
| Arduino Uno | Fingerprint sensor interface |
| Raspberry Pi 3B+ | Central processing unit |
| Fingerprint Sensor (R305) | Biometric authentication |
| 5" Touch Display | User interface |
| Power Bank | Portable power supply |

## Software Stack
- **Python** (Core logic, Telegram bot)
- **Linux Shell Scripting** (Automation)
- **Yagmail** (Email notifications)
- **Telebot API** (Telegram integration)
- **Adafruit Fingerprint Library** (Sensor communication)

## Installation
```bash
# Clone repository
git clone https://github.com/yourusername/Fingerprint-Attendance-System.git

# Install dependencies
pip install -r requirements.txt

# Configure settings
cp config.example.py config.py

Usage
Enroll fingerprints using the enrollment script

Run the main attendance system:

bash
python start.py
Access attendance data via:

Email alerts (automatic)

Telegram bot commands:

/start - Initiate bot
/attendance - Check your records
