
# MPEG-4 Video Encoding Pipeline

This project implements a simplified MPEG-4-inspired video encoder and decoder in Python. It takes a sequence of images as input and generates a compressed binary `.bin` file, which can later be decoded to reconstruct the original frames.

### Key Features
- **Color Space Conversion:** YCbCr conversion.
- **I-Frame Compression:** Discrete Cosine Transform (DCT).
- **P-Frame Compression:** Motion estimation.
- **Entropy Coding:** Run-Length Encoding (RLE) and Lempel-Ziv-Welch (LZW).

### Installation & Usage

Install the required dependencies:

```bash
pip install numpy opencv-python matplotlib
```

Run the encoder:

```bash
python main_encode.py
```

Run the decoder:

```bash
python main_decode.py
```

### Contributors
- **Hind Dellache**
- **Sarah Benchabane**

**Supervisor:** B. Abadli
