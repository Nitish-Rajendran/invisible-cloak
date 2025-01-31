# 🧙‍♂️ The Marauder's Digital Cloak: Python OpenCV Magic 🌟

## ✨ Project Overview
Create your own magical invisibility cloak just like Harry Potter, using Python and computer vision! This script uses OpenCV to make any blue-colored object "disappear" against a background.

## Prerequisites
- Python
- OpenCV
  ```bash
  pip install opencv-python
  ```

## 🔧 Customize Color Range
Modify lower_color and upper_color in the script to match your cloak's exact color in HSV format in line 53 and 54.
### Example
```python
lower_color = np.array([90, 50, 50])  # the lighter shade of your cloak
upper_color = np.array([130, 255, 255])  # the darker shade of your cloak
```

## How It Works
1. Capture background frame
2. Define cloak color range
3. Real-time video processing creates "invisibility"

## Quick Start
```bash
python invisible_cloak.py
```

## Pro Tip
- Wear a solid-colored cloak
- Ensure good lighting
- Press 'q' to quit the magic

## Contributing
Feel free to submit pull requests or open issues if you have any suggestions or improvements.


