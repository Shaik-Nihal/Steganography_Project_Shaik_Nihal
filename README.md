# 🔐 Secure Image Steganography Tool  
> Hide encrypted messages in images using XOR, Base64 & LSB embedding

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20MacOS-lightgrey?style=for-the-badge)

A simple yet powerful GUI tool that enables you to hide and retrieve encrypted messages within PNG images using a secure method that combines XOR cipher, Base64 encoding, and Least Significant Bit (LSB) steganography.

---

## 📌 Features

- ✅ XOR-based text encryption
- ✅ Base64-encoded for binary-safe transport
- ✅ Bit-level embedding using LSB
- ✅ Automatic message length handling
- ✅ Dynamic image preview (resize-aware)
- ✅ Secure decryption with error handling
- ✅ Built with Python and Tkinter

---

## 🧠 How It Works

1. **Encryption**  
   - Message is XOR encrypted using a secret key  
   - Result is Base64-encoded to ensure safe character encoding  
2. **Bit Embedding**  
   - Encrypted string is converted into bits  
   - First 32 bits store the message length  
   - Remaining bits are embedded into image pixels' LSBs  
3. **Decryption**  
   - Extract length → bits → bytes → Base64 decode → XOR decrypt → 🎉 message recovered!

---

## 🖼 GUI Preview

![GUI](https://your-image-link.png) <!-- Replace with a real image or remove -->


---

## 🚀 Getting Started

### ✅ Prerequisites

```bash
pip install opencv-python pillow numpy
```
## 📄 License

This project is free to use under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Shaik Nihal**
[GitHub Profile](https://github.com/Shaik-Nihal/)

Built during an internship as a secure image steganography project.
