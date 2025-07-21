# 🧠 AI-Enhanced Image Compression

Python-based hybrid image compression system combining **Wavelet Transform (DWT)**, **Fourier Transform (DFT)**, and a **Deep Learning Autoencoder**, with optional **KMeans Clustering**. A minimal web interface is provided using **PHP & MySQL (XAMPP)**.

---

## 📦 Features

- Compresses JPEG/PNG images using hybrid ML and signal processing techniques
- DWT + DFT for frequency-domain analysis
- Autoencoder for learning-based image reconstruction
- KMeans clustering (optional) for additional optimization
- PHP-based frontend + MySQL backend for local UI with XAMPP
- Ideal for bandwidth-saving or memory-limited systems

---

## 📸 Demo / Example

- 🎥 [Watch demo video](https://your-demo-link.com)
- Or check the `/examples` folder for:
  - `original.png`
  - `compressed_output.png`

---

## 💻 Usage

### 🧠 Python Compression Scripts

```bash
# Create and activate environment (recommended)
conda create -n compress python=3.9
conda activate compress

# Install dependencies
pip install -r requirements.txt

# Run main autoencoder compression
python python/autoencoder_compress.py
```

---

### 🌐 PHP Web Interface (XAMPP)

1. Install [XAMPP](https://www.apachefriends.org/)
2. Start Apache and MySQL from XAMPP control panel
3. Move `/php` folder to `C:/xampp/htdocs/AI-Enhanced-Image-Compression/`
4. Open phpMyAdmin and import `database/image_log.sql`
5. Open browser and go to:
   ```
   http://localhost/AI-Enhanced-Image-Compression/php/
   ```

---

## 📁 Project Structure

```
AI-Enhanced-Image-Compression/
│
├── python/                # DWT, DFT, Autoencoder code
├── php/                   # Web UI using XAMPP
├── database/              # MySQL schema
├── examples/              # Input/Output sample images
├── requirements.txt       # Python dependencies
└── README.md              # Project overview
```

---

## 📚 Installing

### Python Libraries

```bash
pip install numpy opencv-python matplotlib pywavelets tensorflow scikit-learn
```

### XAMPP Setup

- Install XAMPP and run Apache + MySQL
- Place project folder inside `htdocs/`
- Use browser to access the PHP frontend

---

## 🧠 Compression Flow

```text
[Input Image]
     ↓
[Wavelet Transform (DWT)]
     ↓
[Fourier Transform (DFT)]
     ↓
[Autoencoder (Deep Learning)]
     ↓
[Optional: KMeans Clustering]
     ↓
[Compressed Image]
```

---

## 📬 Author

**Devadarsini K**  
Postgraduate in Electronics & Communication Engineering  
💡 Passionate about AI, embedded systems & real-world ML solutions

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and share.

---

> _⭐️ If you find this project helpful, consider starring the repo or sharing with peers!_
