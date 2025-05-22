
# 🖼️ Python Image Processing Project

## 📘 Overview
This project is a modular Python-based system designed to demonstrate fundamental image processing techniques, including:

- Brightness and contrast adjustment  
- Gaussian blurring  
- Edge detection using the Canny algorithm  
- Noise reduction using Non-local Means Denoising  
- Feature extraction (histogram-based)

The project is implemented with simplicity, clarity, and extendibility in mind.

---

## 🧰 Requirements

Ensure the following Python packages are installed:

```bash
pip install opencv-python numpy matplotlib
```

Or in Google Colab:

```python
!pip install opencv-python numpy matplotlib
```

---

## 🗂️ Project Structure

```
image_processing_project/
├── main.py                # Main execution script
├── processing.py          # Contains all processing functions
├── input.jpg              # Input image file
├── results/               # Output folder for processed images
└── README.md              # This file
```

---

## 🧪 How to Run the Code

### 1. In Google Colab
Upload `main.py` and your input image (e.g., `input.jpg`)  
Run the cells step-by-step. Each function will display and save its result in `/content/results`.

### 2. Locally
```bash
python main.py
```
Make sure your image is in the correct directory and named accordingly in the script.

---

## 🧠 Techniques Used

### 1. **Brightness & Contrast Adjustment**
- Enhances or reduces image clarity and visibility.
- Controlled via `alpha` (contrast) and `beta` (brightness) parameters.

### 2. **Gaussian Blur**
- Reduces image details and noise using a 2D Gaussian kernel.

### 3. **Canny Edge Detection**
- Detects edges and outlines of objects by finding intensity gradients.

### 4. **Non-local Means Denoising**
- Removes noise intelligently while preserving important features.

### 5. **Feature Extraction**
- Grayscale histogram used as a simple descriptor for image analysis or classification preparation.

---

## 📥 Supported Input Formats

- `.jpg`  
- `.png`  
- `.tif`  

Robust error handling is included for unsupported formats and missing files.

---

## 💾 Output

Each processing step saves an output image in the `results/` folder with meaningful filenames such as:
- `adjusted_brightness_contrast.jpg`
- `blurred.jpg`
- `edges.jpg`
- `denoised.jpg`
- `features.npy` (if used for numerical feature data)

---

## ⚙️ Best Practices Followed

- PEP8-compliant, modular, and well-commented code.
- Memory-efficient operations with minimal image copying.
- Fault-tolerant design with exception handling.

---

## 🚀 Bonus (Optional GUI)

A simple GUI can be created using HTML/CSS/JS with OpenCV.js or a Python-based interface (e.g., with `tkinter` or `streamlit`) to control steps visually.

---

## ⚠️ Limitations

- Feature extraction is simple and can be improved (e.g., using SIFT, ORB, etc.).
- The current pipeline is sequential and non-interactive without a GUI.

---

## 📅 Deadline & Submission

- **Deadline:** 25-05-2025  
- **Submission:** ZIP file of the full project or GitHub repository link

---

## 👨‍💻 Author
**Mohamed Sayed Bin Abdullah**

