# 🧾 Python Billing System with QR Code Generator

A simple, terminal-based billing system for retail stores built in Python. It simulates a store's checkout process by reading product data from a file, allowing purchases, updating inventory, and generating a detailed invoice with a QR Code.

---

## 📌 Features

- 🛒 Interactive customer purchase input
- 📂 Reads and writes product information from/to a file
- 🔄 Updates stock quantities based on purchases
- 💵 Calculates total billing amount
- 🧾 Generates invoice text file per customer
- 📱 Creates and displays a QR code of the purchase details
- 👤 Supports multiple customers in a session

---

## 🛠️ Technologies Used

- Python 3.x
- [`qrcode`](https://pypi.org/project/qrcode/)
- [`Pillow (PIL)`](https://pypi.org/project/Pillow/)

---

## 📁 Project Structure

```bash
python-billing-system/
│
├── read.py             # Reads product data from file
├── purchase.py         # Handles customer purchase input
├── write.py            # Updates product file with new stock
├── main.py             # Main program logic and loop
├── products.txt        # Product database (sample data file)
├── invoice.txt         # Generated invoice file
├── qr_code.png         # QR code image output
└── README.md           # Project documentation

```

---
## 📦 Installation & Setup
###Clone the Repository

- git clone https://github.com/Abhavyaj/Billing-System-with-QR-Code-Generator.git
- cd Billing-System-With-QR-Code-Generator-main

---

## Install Required Libraries

- pip install qrcode[pil]
- pip install Pillow

---

## 🔁 Customer Loop Support

### Are there any new customers? (Y/N):
- Enter Y to process the next customer.
- Enter N to exit the application.

--- 

## 📄 License
This project is licensed under the MIT License.

---

## 🤝 Contributing
Pull requests are welcome! For significant changes, please open an issue first.
