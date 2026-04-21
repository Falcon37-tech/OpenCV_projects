
✏️ Image to Pencil Sketch using OpenCV

Convert a normal image into a realistic pencil sketch using Python and OpenCV.

📸 Demo
🖼️ Original Image


<img width="1024" height="897" alt="joke" src="https://github.com/user-attachments/assets/47ccf4e5-f200-45bd-b75a-ee3334ee552e" />



✏️ Pencil Sketch Output







📌 Features
Convert images into pencil sketches
Fast and efficient processing
Beginner-friendly project
Works in VS Code / local system
🛠️ Technologies Used
Python
OpenCV (cv2)
NumPy
📂 Project Structure
Image-to-Pencil-Sketch/
│── main.py
│── images/
│     ├── original.png
│     ├── sketch.png
│── README.md
⚙️ Installation
git clone https://github.com/your-username/image-to-pencil-sketch.git
cd image-to-pencil-sketch
pip install opencv-python numpy
▶️ Usage
image = cv2.imread("images/original.png")
python main.py
🧠 How It Works
Convert image to grayscale
Invert grayscale image
Apply Gaussian blur
Blend images to create sketch effect
📷 Example Output
Original	Sketch

	





🚀 Future Improvements
Add GUI (upload image)
Save output automatically
Multiple sketch styles
