# FaceLockApp: Face Recognition with File Encryption and Decryption

## Description
FaceLockApp is a Python-based application that uses face recognition for secure file encryption and decryption. Unauthorized access attempts are logged and reported via Telegram alerts.

## Features
- **Face Training**: Capture and store user face encodings.
- **File Encryption**: Encrypt files securely using the Fernet encryption protocol.
- **File Decryption**: Verify the user’s face before decrypting files.
- **Unauthorized Access Reporting**: Capture unknown faces and send alerts via Telegram.

## Libraries Used
- `kivy==2.2.1` (UI Framework)
- `opencv-python==4.8.0.74` (Camera capture and processing)
- `face-recognition==1.3.0` (Face recognition)
- `pyttsx3==2.90` (Text-to-speech)
- `cryptography==41.0.4` (Encryption and decryption)
- `python-telegram-bot==20.5` (Telegram integration)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FaceLockApp.git
   cd FaceLockApp

