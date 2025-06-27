
# How to Use

1. Launch the Tool
Run the script using Python:
python stegotool.py

2. Add Data to Hide
Click the Add ➕ button to choose what you want to hide:
- Text – Allows you to type a secret message
- Image, Video, or Document – Opens file selector for embedding

3. Encode Data
Click Encode 🔒 and follow these steps:
1. Select the cover image (PNG/BMP)
2. Set an optional password (for encryption)
3. Save the output stego-image

4. Decode Data
Click Decode 🔓 and follow these steps:
1. Select the stego-image
2. Enter the password (if set during encoding)
3. Extracted message appears or file is saved

After 3 incorrect password attempts, the tool temporarily locks out access with increasing wait time.

5. Generate Image
Click Generate ⚙️ to create a blank image with custom dimensions for use as a carrier image.

6. Help
Click Help ❓ for a summary of the tool's usage and security features.

# Note : File Types Supported
- Image formats: .png, .bmp
- Data types: Text, Images, Videos, Documents (any file type)

# Requirements
- Python 3.x
- PIL (Pillow)
- Tkinter (usually included with Python)

# License
This project is intended for educational and research use only.
# stegotool.py file contain the python code to run this code.
