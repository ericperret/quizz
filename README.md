
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Pure HTML/JS](https://img.shields.io/badge/Pure-HTML%2FJS-blue.svg)](#)
[![Educational](https://img.shields.io/badge/Purpose-Educational-orange.svg)](#)

**Interactive DVB-S satellite transmission pipeline tutorial** — From JPEG image to QPSK modulation.

![Screenshot](screenshot.png)

## 🚀 Features

Step-by-step visualization of the complete DVB-S transmission chain:

1. **Camera Capture** — Source image acquisition
2. **Macroblocks** — 8x8 block decomposition
3. **DCT** — Discrete Cosine Transform
4. **Quantization** — Lossy compression
5. **Zigzag Scan** — Coefficient reordering
6. **RLE + Huffman** — Entropy coding
7. **Elementary Stream** — Video ES packaging
8. **PES** — Packetized Elementary Stream
9. **Transport Stream** — MPEG-TS multiplexing
10. **PRBS** — Energy dispersal scrambling
11. **Reed-Solomon** — FEC outer coding (204,188)
12. **Interleaving** — Burst error protection
13. **Convolutional Code** — FEC inner coding
14. **QPSK** — Quadrature Phase Shift Keying
15. **SRRC Filter** — Pulse shaping

## 🛠️ Tech Stack

- Pure HTML/CSS/JavaScript
- No external dependencies
- Each step is a standalone HTML page
- Real calculations, not just diagrams

## 📖 Usage

Open any \`pageXX-*.html\` file in your browser to explore that stage of the pipeline.

## 🎓 Educational Purpose

Learn how digital satellite TV works, from video compression to RF modulation. Each page includes:
- Theory explanation
- Interactive visualization
- Real-time calculations

## 📄 License

CC BY-NC 4.0

## 👤 Author

**Eric PERRET** — [GitHub](https://github.com/ericperret)