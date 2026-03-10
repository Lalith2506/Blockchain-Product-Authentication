# 🔐 Blockchain-Based Product Authentication System

## 📌 Overview
Counterfeit products are a growing problem in many industries, affecting both consumers and manufacturers. This project explores how blockchain technology can be used to build a secure and transparent system for verifying product authenticity.

The application converts barcode data into a cryptographic hash and stores it within a blockchain structure. Because blockchain records are immutable, the stored information remains secure and cannot be modified after it is recorded. This makes it possible to verify whether a scanned product barcode belongs to an authentic product or a counterfeit one.

The goal of this project is to demonstrate how blockchain can be applied to real-world authentication systems in a simple and understandable way.

---

## ✨ Key Features

🔗 **Blockchain-Based Security**  
Product information is stored within a blockchain structure, ensuring that the data remains tamper-resistant.

🖋 **Digital Signature Generation**  
Barcode images are converted into unique SHA-256 hash signatures that represent each product.

🖥 **User-Friendly Interface**  
A graphical interface built with Tkinter allows users to easily interact with the system.

🔍 **Product Verification System**  
Users can verify products by scanning or uploading barcode images and comparing them with stored blockchain records.

🚫 **Fake Product Detection**  
The system identifies barcode images that do not match the registered blockchain data.

---

## 🧩 System Modules

### 📦 Product Registration
Users can enter product information and upload the corresponding barcode image.  
The system generates a digital hash and stores the product data inside the blockchain.

### 🔎 Product Data Retrieval
Stored product details can be retrieved using a product ID.

### 🛡 Barcode Authentication
Users can upload a barcode image and the system verifies it against blockchain records to determine whether the product is genuine or potentially counterfeit.

---

## ⚙️ How the System Works

1️⃣ The barcode image is processed and converted into a digital hash using **SHA-256**.  
2️⃣ The product data and hash value are stored in a new block within the blockchain.  
3️⃣ Each block verifies the integrity of the previous block before being added.  
4️⃣ When a barcode is scanned, its hash is generated and compared with stored blockchain records.  
5️⃣ If the values match, the product is verified as authentic.

---

## 💻 Technologies Used

🐍 **Python 3**  
🖼 **Tkinter** – Graphical User Interface  
🔐 **SHA-256 Hashing** using Python hashlib  
⛓ **Custom Blockchain Implementation**

---

## 🚀 Getting Started

### Clone the repository

git clone https://github.com/Lalith2506/blockchain-product-authentication.git

### Install required dependencies

pip install -r requirements.txt

### Run the application

run.bat

---

## 🌍 Possible Applications

📦 Supply chain product authentication  
🎓 Academic certificate verification  
📄 Document validation systems  
🏷 Brand protection against counterfeit products

---

## 🤝 Project Note
This project was developed as part of a collaborative academic project exploring practical applications of blockchain technology in authentication systems.
