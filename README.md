# 🖼️ Image Verification Using Google Lens

This Python-based tool automates the process of verifying an image using **Google Lens** and organizes it by moving the image into a folder named after its most likely source or best match.

---

## 📌 Project Overview

The goal of this project is to:

- Accept an image as input
- Use **Google Lens** via automated browser interaction to identify the image's source
- Automatically create a folder named after the identified source
- Move the image into this folder for easy classification and organization

---

## 🔧 Features

- ✅ Google Lens image verification via Selenium
- ✅ Automatically moves images into source-named folders
- ✅ User-friendly and simple to run
- ✅ Supports `.jpg`, `.png`, `.jpeg`, etc.

---

## 🚀 How It Works

1. Opens [Google Images](https://images.google.com)
2. Clicks on the Google Lens icon
3. Uploads the image manually (automation for uploads is limited due to browser security)
4. Extracts the best match or title from the Google Lens result
5. Moves the image to a folder named after the match

---

## 🧰 Requirements

Make sure you have Python 3.x installed.

Install dependencies with:

```bash
pip install selenium webdriver-manager
Also, ensure you have Google Chrome installed — this script uses ChromeDriver.

📝 Usage
1. Prepare an image
Place your image (e.g., sample.jpg) in the project folder.

2. Run the script
bash
Copy
Edit
python image_verifier.py
The script will:

Open Chrome browser

Navigate to Google Images

Ask you to manually upload the image

Wait for the result

Move the image into a new folder named after the identified source

Example:
If Google Lens identifies the image as "Eiffel Tower", it will move sample.jpg into a folder called Eiffel Tower.

📂 Folder Structure
mathematica
Copy
Edit
📁 Image-Verification-Using-Google-Lens
├── image_verifier.py
├── sample.jpg
├── README.md
└── 🗂️ Eiffel Tower/
      └── sample.jpg
⚠️ Limitations
🔒 Manual Image Upload: Due to browser security, file uploads must be done manually unless additional tools like PyAutoGUI or AutoIt are used.

🌐 Internet Required: Relies on live Google Lens results.

❌ No API Use: Google Lens doesn’t offer a public API, so we rely on web automation.

📌 Future Improvements
Full automation of image upload using PyAutoGUI or OS-specific tools

Headless browser support

GUI version with drag-and-drop support

Batch image processing

🤖 Tech Stack
🐍 Python 3

🌐 Selenium WebDriver

🧠 Google Lens (via browser automation)

🧰 Chrome + ChromeDriver

📄 License
This project is open-source and available under the MIT License.

🙋‍♂️ Author
Image Verification Using Google Lens
Developed by Aamir Hussain– 2025
Feel free to contribute or fork!
