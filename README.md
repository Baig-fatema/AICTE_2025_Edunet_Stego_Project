# AICTE_2025_Edunet_Stego_Project
# StegoCrypt - Image-Based Steganography Project 🔐🎨  

## 📌 Project Overview  
StegoCrypt is a **Python-based steganography tool** that allows users to **securely hide and retrieve messages within an image** by modifying pixel values. Using **OpenCV (cv2) and ASCII encoding**, the project ensures **covert communication**, with a password-protected decryption mechanism for added security.  

## 🚀 Features  
✅ **Image-Based Steganography** – Hides text messages within an image without altering its visible quality.  
✅ **Password-Protected Decryption** – Ensures that only authorized users can retrieve the hidden message.  
✅ **Lightweight & Efficient** – Uses simple **ASCII encoding** for embedding messages securely.  
✅ **Cross-Platform Compatibility** – Runs on **Windows & Linux** using Python.  
✅ **No Additional Storage Needed** – The message is directly stored inside the image pixels.  
✅ **User-Friendly Execution** – Simple CLI-based input/output for encryption and decryption.  

## 🛠️ Technologies Used  
- **Python** 🐍  
- **OpenCV (cv2)** – For image processing  
- **OS Module** – For system operations  

## 🔧 Installation & Usage  
### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Baig-fatema/AICTE_2025_Edunet_Stego_Project.git
cd AICTE_2025_Edunet_Stego_Projec
```
### 2️⃣ Install Dependencies
```bash
pip install opencv-python
```
### 3️⃣ Run the Encryption Script
```bash
python stego.py
```
### 4️⃣ Run the Decryption Script
```bash
python stego.py
```
## 📜 How It Works
### 1️⃣ The user inputs a secret message and password.
### 2️⃣ The script modifies image pixel values to store the message.
### 3️⃣ The modified image (stego image) is saved as encryptedImage.jpg.
### 4️⃣ To decrypt, the user provides the correct passcode to extract the hidden text.

## 🔒 Security & Limitations
### ⚠ Only ASCII characters are supported for message encoding.
### ⚠ Ensure the image has sufficient pixel space to store the message.
### ⚠ Encrypted images should not be compressed, as it may distort the hidden data.

## 🔮 Future Scope
🚀 Enhancing Encryption – Integrating stronger cryptographic techniques.
🚀 Supporting Audio/Video Files – Expanding beyond images for steganography.
🚀 AI-Based Detection Prevention – Making messages more resilient to steganalysis tools.
🚀 Mobile & Web Applications – Creating a UI-based platform for easy encryption/decryption.

## 📌 Contributing
We welcome contributions! Feel free to submit pull requests or open issues to improve the project.



