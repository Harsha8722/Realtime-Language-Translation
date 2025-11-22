📌 Real-Time Language Translator (Text + Image OCR)

A desktop-based Language Translator Application built using Python.
You can translate typed text or text extracted from images (OCR) into multiple languages in real-time.

This project uses:

Tkinter – GUI

EasyOCR – Image text extraction

GoogleTranslator (deep-translator) – Translation

Pillow – Image processing

🚀 Features
✔ Real-Time Text Translation

Automatically translates as you type

Manual translate option

Supports multiple languages

Clean and simple UI

✔ Image Translation (OCR)

Upload any image (PNG, JPG, JPEG…)

Extracts text using EasyOCR

Instantly translates extracted text

✔ Multi-language Support

Supports languages like:

English

Tamil

Hindi

German

Spanish

French

Chinese

Japanese

Korean
…and many more.

🛠 Technologies Used
Purpose	Library
GUI	Tkinter
OCR	EasyOCR
Translation	Deep Translator
Image Processing	Pillow
Threading	Python Thread API
📥 Installation
1. Clone the Repo:
git clone https://github.com/Harsha8722/Realtime-Language-Translation.git
cd your-repo-name

2. Install Dependencies:
pip install easyocr pillow deep-translator


If EasyOCR needs torch:

pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

▶️ Run the Application
python translator.py


The GUI window will open.

📂 Project Structure
│── translator.py
│── README.md
│── (optional) screenshot.png





