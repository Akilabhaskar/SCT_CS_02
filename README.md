# Image Encryption Tool in Python

A Python project that demonstrates *image encryption and decryption* using three different methods:
- *XOR* with a key
- *Addition* with modular wrapping
- *Pixel swapping* (row and column reversal)

This project is designed for learners and developers interested in exploring how classical cryptography concepts can be applied to digital images.

---

## Features
- Encrypt images using XOR, addition, or pixel-swapping
- Decrypt images back to their original form
- Supports any image format compatible with Pillow (.png, .jpg, .jpeg, etc.)
- Simple, modular functions for easy extension

---

##  How It Works
1. *XOR Method*  
   Each pixel value is XORed with a key.  
   Example: pixel ^ key

2. *Addition Method*  
   Each pixel value is increased by the key, wrapped around at 256.  
   Example: (pixel + key) % 256

3. *Swap Method*  
   Rows and columns of the image are reversed, scrambling the structure.

Decryption reverses the process depending on the chosen method.

---
