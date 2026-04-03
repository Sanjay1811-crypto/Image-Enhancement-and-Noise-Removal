# Image-Enhancement-and-Noise-Removal

A modern **Digital Image Processing (DIP) web application** that performs real-time image enhancement using classical techniques like grayscale conversion, noise addition, median filtering, and histogram equalization — all directly in the browser.

---

## 🚀 Features

- 📂 Drag & Drop Image Upload  
- ⬜ Grayscale Conversion  
- ⚡ Salt-and-Pepper Noise  
- 🔲 Median Filtering (5×5 kernel)  
- 📊 Histogram Equalization  
- 📈 Histogram Visualization (RGB + Luminance)  
- 📉 Overlay & Difference Histogram Comparison  
- 📊 Image Statistics (Mean, Std Dev, Entropy, Skewness)  
- 🔄 Processing Pipeline Visualization  
- ⚡ Fully Client-Side (No backend required)

---

## 🧠 Processing Pipeline

```
LOAD → GRAYSCALE → NOISE → DENOISE → ENHANCE
```

---

## 📊 Image Processing Techniques

### 1. Grayscale Conversion
Converts RGB image to luminance using:
```
Y = 0.299R + 0.587G + 0.114B
```

### 2. Noise Addition
Applies **salt-and-pepper noise** by randomly setting pixels to black or white.

### 3. Median Filtering
- Uses a **5×5 kernel**
- Replaces each pixel with the median of neighbors
- Effective for removing impulse noise

### 4. Histogram Equalization
- Enhances contrast
- Operates on luminance channel
- Redistributes intensity values for better visibility

---

## 📈 Metrics Computed

- Mean Intensity  
- Standard Deviation  
- Entropy (information content)  
- Skewness (distribution shape)  
- Peak Bin & Frequency  

---

## 🛠️ Tech Stack

- **HTML5 Canvas** – Image rendering and processing  
- **JavaScript (Vanilla)** – Core logic and algorithms  
- **CSS (Modern UI)** – Responsive and interactive design  

---

## 📂 Project Structure

```
index.html   # Complete application (UI + logic)
```

---

## ▶️ How to Run

1. Clone the repository:
```
git clone https://github.com/your-username/dip-image-enhancement.git
```

2. Open the file:
```
index.html
```

No installation or setup required 🚀

---

## 📌 Applications

- Medical Image Preprocessing  
- Surveillance Image Enhancement  
- Educational Tool for DIP concepts  
- Image Analysis & Visualization  

---

## ⚠️ Limitations

- May cause over-enhancement in some cases  
- Not adaptive (basic histogram equalization)  
- No backend or image saving feature  

---

## 🔮 Future Improvements

- CLAHE (Adaptive Histogram Equalization)  
- Bilateral Filtering (edge-preserving smoothing)  
- Image download/export feature  
- Flask backend integration  
- Deep learning-based enhancement  

---

## 👨‍💻 Author

**Nuzella Prabhakara Sanjay**  
BCSE403L – Digital Image Processing Lab  
VIT University  

---

## 📜 License

This project is for educational purposes only.
