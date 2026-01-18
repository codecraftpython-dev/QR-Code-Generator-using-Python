# 📌 QR Code Generator using Python

A simple and advanced QR Code Generator built with Python using the qrcode library.
This project demonstrates both basic and customizable QR code generation with support for colors, size control, and high error correction.

✨ Features
✅ Generate QR codes for URLs and text
🎨 Custom QR code colors (foreground & background)
📐 Adjustable box size and border
🛡 High error correction level for better scan reliability
💾 Save QR codes as PNG image files
🧠 Beginner-friendly and easy to understand

🛠 Technologies Used
Python 3
qrcode library
Pillow (PIL) for image generation

📂 Project Structure
qr-code-generator/
│
├── qr_generator.py
├── README.md
├── requirements.txt
└── My_Website.png

📦 Installation
Make sure Python is installed, then run:
pip install qrcode[pil]
Or using requirements.txt:
pip install -r requirements.txt

▶ Usage
Run the Python file:
python qr_generator.py
After execution, a QR code image will be generated and saved in the project directory.

🧪 Example Code
Basic QR Code
import qrcode as qr
img = qr.make("https://www.youtube.com/")
img.save("Youtube.png")

📸 Output
![QR Code Output](My_Website.png)
Fully scannable using any QR scanner app

🎯 Use Cases
Website & blog sharing
Learning Python libraries
Educational mini-projects
Portfolio projects
Link sharing via QR

🤝 Contributing
Contributions are welcome!
Feel free to fork this repository and submit a pull request.

📄 License
This project is licensed under the MIT License — free to use and modify.

⭐ Support
If you like this project, don’t forget to star ⭐ the repository!
