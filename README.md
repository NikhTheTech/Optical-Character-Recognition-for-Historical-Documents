# 🏛 Optical Character Recognition for Historical Documents  

An end-to-end OCR (Optical Character Recognition) system built using **Python, OpenCV, Tesseract, and Tkinter**, designed specifically for processing and translating historical documents.  

This project allows users to:  

- **Upload scanned images or PDFs** of historical texts  
- **Preprocess images** (denoising, contrast enhancement, sharpening, deskewing) for improved OCR accuracy  
-  **Extract text** using Tesseract OCR (supports multiple languages)  
- *Automatically detect language** of the extracted text  
- **Translate text** into English (or other target languages)  
- **Export results** as **PDF** or **Word (.docx)** files  
- **Use an interactive GUI** with **light/dark mode support**  

---

## 🚀 Features  

- **Advanced Preprocessing Pipeline**  
  - Noise detection and removal  
  - Contrast enhancement  
  - Image sharpening  
  - Automatic deskewing  
  - Adaptive thresholding for better binarization  

- **Multi-language OCR**  
  - Supports **English, French, Spanish, and German** (can be extended easily)  
  - Uses `pytesseract` with custom OCR configuration for accuracy  

- **Automatic Language Detection & Translation**  
  - Detects the source language using `langdetect`  
  - Translates non-English text to English using `deep-translator`  

- **Export Options**  
  - Save results as **PDF** (auto-incrementing filenames)  
  - Save results as **Word document**  

- **User-Friendly GUI**  
  - Built with Tkinter  
  - Upload images with a single click  
  - View OCR output and translated output in pop-up windows  
  - Toggle **dark mode** for better readability  

---

## ⚙️ Installation  

### 1️⃣ Clone the Repository  
```
git clone https://github.com/NikhTheTech/Optical-Character-Recognition-for-Historical-Documents
cd Optical-Character-Recognition-for-Historical-Documents
```
### 2️⃣ Install Dependencies
```
pip install -r requirements.txt
```
### 3️⃣ Install Tesseract OCR
- Windows: Download Tesseract

- Linux (Debian/Ubuntu):
```
sudo apt install tesseract-ocr
```
- macOS:
```
brew install tesseract
```
## 📦 Requirements
Python 3.8+

Libraries:

   - nginx
   - Copy code
   - tkinter
   - pillow
   - opencv-python
   - pytesseract
   - deep-translator
   - langdetect
   - numpy
   - fpdf
   - python-docx
## ▶️ Usage
Run the application:
```
python main.py
```
1. Upload Image → Select a scanned document or image

2. Perform OCR & Translate → Extracts and translates text

3. Save Output → Choose PDF or Word format

4. Toggle Dark Mode → Switch between light/dark UI themes

##📊 Example
| Input (Historical Document)                                                              | OCR Output (Detected Text)        | Translated Output (English) |
| ---------------------------------------------------------------------------------------- | --------------------------------- | --------------------------- |
| ![33](https://github.com/user-attachments/assets/687504b4-e495-4695-a5a7-ba39106d12e5)   | *"Bonjour, comment allez-vous "* | *"Hello, how are you"*     |



