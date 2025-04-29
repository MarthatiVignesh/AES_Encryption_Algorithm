# AES Cryptosystem Project

This repository contains the implementation of the Advanced Encryption Standard (AES) as part of the CS1702 Network Security Assignment. The project is written entirely in python and demonstrates encryption and decryption functionalities.

---

## Project Structure

```
AES_Encryption_Algorithm/ 
├── Code/ 
│   └── AES_CS22B1028_Implementation.py # Python implementation of AES 
│   
├── Report/ 
│   └── AES_CS22B1028_Report.pdf        # Detailed project report 
│   
├── Result/ 
│   └── AES_CS22B1028_Results.png       # Result screenshot of AES execution 
│ 
└── README.md                           # Project description and instructions
```


---

## About AES

**AES (Advanced Encryption Standard)** is a symmetric block cipher standardized by NIST. It is widely used for data encryption due to its efficiency, security, and resistance to cryptographic attacks.

AES works on fixed block sizes of 128 bits and supports key sizes of 128, 192, or 256 bits. It uses multiple rounds of substitution, permutation, mixing, and key addition.

---

## Features

- Key generation (128/192/256-bit support)
- AES Encryption and Decryption in ECB/CBC mode
- Padding handling for plaintext blocks
- CLI-based user interaction
- Handles both text and file encryption/decryption
- Technical documentation and output visualization

---

## How to Run the Code

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/AES-Project.git
cd AES-Project
```

### 2. Run the AES Script
```bash
python Code/AES_CS22B1028_Implementation.py
```
You will be prompted to enter a plaintext message or file to encrypt and will see encrypted and decrypted results.

---

## Report

A comprehensive explanation of the AES algorithm is available in the [`Report/AES_CS22B1028_Report.pdf`](Report/AES_CS22B1028_Report.pdf). It covers:
- Overview
- Block cipher design and round structure
- Methodology
- Applications
- Conclusion

---

## Result

An example result of AES encryption is available in the [`Result/AES_CS22B1028_Results.jpg`](Result/AES_CS22B1028_Results.jpg) file.

---

## Applications of RSA

- Secure Communications
- File Encryption
- Embedded Systems

---

