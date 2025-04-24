# Voice Assistant with Email OTP Verification

This project combines voice-based interactions with email-based OTP (One-Time Password) verification using Python. The assistant recognizes speech, responds with synthesized voice, opens popular websites, and can send OTPs for email-based identity confirmation.

## 🔧 Features

- 🎤 **Speech Recognition** using `speech_recognition`
- 🔊 **Text-to-Speech** responses using `pyttsx3`
- 🌐 **Web Browser Automation** for websites like Amazon, Flipkart, and Codegnan
- 📧 **OTP Verification System** using `smtplib` and `email` modules
- 🛡️ **Basic Email Authentication** (Note: ensure secure handling of credentials)

## 🧠 How It Works

1. The assistant greets the user and listens for voice commands.
2. Based on the command, it can:
   - Respond with a voice message
   - Open websites
   - Send an OTP to the entered email address
3. The OTP is randomly generated and sent via email.
4. User is prompted to enter the OTP to complete verification.

## 📁 Project Structure

```plaintext
.
├── sample.py     # Main voice assistant logic
└── otp.py        # Email OTP sending and verification

🔗 GitHub Repository
📁 Project Link: https://github.com/PaidimarriHarshavardhan/Speech-Recognition
