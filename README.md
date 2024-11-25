
# **OPTICAL CHARACTER RECOGNITION**

## Description
This project involves implementing Optical Character Recognition (OCR) using Python, OpenCV, and Tesseract. OCR technology extracts text from images or scanned documents and converts it into readable and audible text.

### **Key Features:**
- Text detection and recognition using Tesseract OCR.
- Object detection using deep learning techniques such as YOLO (You Only Look Once).
- Image processing with OpenCV to enhance text recognition accuracy.

---

### **Technologies Used:**
- **OpenCV**: For image processing and manipulation.
- **Tesseract OCR**: Engine for character recognition.
- **YOLOv8**: For object detection in images and videos.
- **Python Libraries**: NumPy, Matplotlib, and PIL.

---

### **Project Setup:**
1. **Dependencies Installation:**
   ```bash
   pip install opencv-python pytesseract ultralytics
   sudo apt install tesseract-ocr
   ```


2. **Key Steps in the Notebook:**
   - Load and display images using OpenCV.
   - Convert images to grayscale for better OCR accuracy.
   - Apply image processing techniques like erosion and dilation.
   - Perform text extraction with Tesseract.
   - Use YOLOv8 for object detection in complex images.

### **Object Detection**

![Alt text](https://raw.githubusercontent.com/Punam918/Optical_Character_Recognition/refs/heads/master/images/detected_image.png)


### **Original Textfile**

![Alt text](https://raw.githubusercontent.com/Punam918/Optical_Character_Recognition/refs/heads/master/images/textfile_original.png)


### **ConvertedToGray**

![Alt text](https://raw.githubusercontent.com/Punam918/Optical_Character_Recognition/refs/heads/master/images/togray.png)

### **ToWords**
![Alt text](https://raw.githubusercontent.com/Punam918/Optical_Character_Recognition/refs/heads/master/images/towords.png)






