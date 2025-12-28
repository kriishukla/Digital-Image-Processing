# Digital Image Processing [2025] - Course Work

A comprehensive collection of Jupyter notebooks covering various Digital Image Processing concepts and techniques.

## 📋 Project Overview

This project contains practical implementations and solutions for Digital Image Processing coursework, including image transformations, filtering, edge detection, video calculations, and frame matching techniques.

---

## 📚 Notebook Contents

### 1. **01_GIF_Frame_Matching.ipynb**
- **Topic:** GIF Frame Edge Signature Extraction
- **Key Concepts:**
  - Loading GIF frames and extracting RGBA data
  - Edge signature extraction from image sides (left, right, top, bottom)
  - Animated GIF frame matching and comparison
  - Alpha channel weighted color profiling
  - Downsampling and interpolation techniques

---

### 2. **02_Data_Processing.ipynb**
- **Topic:** Large-Scale Data Processing
- **Key Concepts:**
  - Batch image processing
  - Data pipeline implementation
  - Efficient numpy-based computations
  - CSV data handling

---

### 3. **03_Image_Transformations.ipynb**
- **Topic:** Image Enhancement and Transformations
- **Key Concepts:**
  - Logarithmic transformation
  - Gamma correction
  - Contrast adjustment with multiple c-values and gamma parameters
  - Histogram equalization and analysis
  - Visualization of transformations across multiple test images (Lighthouse, Sunset, Trees)

---

### 4. **05_HDTV_Video_Calculations.ipynb**
- **Topic:** Video Format Specifications and Storage Calculations
- **Key Concepts:**
  - HDTV resolution specifications (1125 lines × 16:9 aspect ratio)
  - Pixel resolution calculations
  - Storage requirements for uncompressed video
  - Downsampling effects on storage (2× reduction in both dimensions)
  - Quantization level impact on file size
  - Real-world calculations for 2-hour HDTV movies
  - Format: 30 fps, 24-bit color (RGB)

**Example Calculations:**
- Original 2-hour HDTV movie (uncompressed): ~1,357.87 GB
- Downsampled (0.5× in each dimension): ~339.16 GB
- 12-bit quantization (50% reduction): ~678.93 GB

---

### 5. **06_Image_Filtering.ipynb**
- **Topic:** Image Filtering and Convolution Operations
- **Key Concepts:**
  - Spatial filtering techniques
  - Kernel-based filtering
  - Blur filters (box, Gaussian)
  - Edge detection filters
  - Filter visualization and analysis
  - Morphological operations
  - Bilateral and median filtering
  - Frequency domain filtering
  - Adaptive filtering
  - Multi-scale filtering approaches

---

## � Assignment Documents

The following PDF files contain detailed assignment specifications and solutions:

- **Assignment_1.pdf** - Foundational concepts and basic image processing
- **Assignment_2.pdf** - Advanced filtering and transformations
- **Assignment_3.pdf** - Video specifications and calculations
- **Assignment_4.pdf** - Complex image processing applications

---

## �🛠️ Technologies & Libraries

- **Python 3.x**
- **NumPy** - Numerical computations and array operations
- **OpenCV (cv2)** - Computer vision and image processing
- **PIL/Pillow** - Image I/O and manipulation
- **Matplotlib** - Data visualization and plotting
- **SciPy** - Scientific computing utilities

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install numpy opencv-python pillow matplotlib scipy
```

### Running the Notebooks

1. Open Jupyter Notebook/Lab:
   ```bash
   jupyter notebook
   ```

2. Navigate to the notebook directory and open any `.ipynb` file

3. Run cells sequentially using `Shift + Enter`

---

## 📊 Learning Outcomes

By completing these notebooks, you will understand:

- ✅ Image representation and color spaces (RGB, RGBA, grayscale)
- ✅ Image enhancement techniques (logarithmic, gamma transformations)
- ✅ Spatial filtering and convolution operations
- ✅ Video format specifications and storage optimization
- ✅ GIF frame processing and animation analysis
- ✅ Histogram analysis and equalization
- ✅ Efficient image processing pipelines
- ✅ Performance considerations in digital image processing

---

## 📝 Notes

- Each notebook is self-contained with necessary imports and explanations
- Images used in demonstrations (lighthouse.png, sunset.png, trees.png) should be placed in the working directory
- Cell outputs (images, plots) are preserved for reference
- Code is organized with clear section markers and comments

---

## 👤 Course Information

- **Student ID:** 2022254
- **Course:** Digital Image Processing [2025]
- **Created:** December 28, 2025

---

## 📖 References

- Digital Image Processing fundamentals
- OpenCV documentation
- NumPy and SciPy tutorials
- Image processing best practices and optimization techniques

