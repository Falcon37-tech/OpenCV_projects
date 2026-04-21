✏️ Image to Pencil Sketch using OpenCV

Convert a normal image into a realistic pencil sketch using Python and OpenCV.

🖼️ Original Image

<img width="1024" height="897" alt="joke" src="https://github.com/user-attachments/assets/47ccf4e5-f200-45bd-b75a-ee3334ee552e" />

✏️ Pencil Sketch Output

<img width="627" height="415" alt="sketch" src="https://github.com/user-attachments/assets/0c1c3c21-2a7b-460b-b375-8e1406d13e13" />

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
<img width="627" height="415" alt="grey" src="https://github.com/user-attachments/assets/b54b85de-8daf-45a3-92c2-d1074fd84a77" />

Invert grayscale image
<img width="627" height="415" alt="gussainscale" src="https://github.com/user-attachments/assets/ce1668c2-14ed-496a-a37c-94bbcf187982" />

Apply Gaussian blur
<img width="627" height="415" alt="blur" src="https://github.com/user-attachments/assets/85dc5906-3b9d-414f-bd7d-d8b88770f6ee" />

Blend images to create sketch effect
<img width="627" height="415" alt="sketch" src="https://github.com/user-attachments/assets/70742037-5d17-4903-84df-bcc62341970f" />


📷 Example Output
Original	Sketch

	
<img width="627" height="415" alt="Screenshot 2026-04-21 164631" src="https://github.com/user-attachments/assets/e28431d2-6c22-4f67-bbff-9bd674b802c6" />        <img width="627" height="415" alt="sketch" src="https://github.com/user-attachments/assets/50f3d46d-f32a-488b-8486-6cac75ecc9c0" />






🚀 Future Improvements
Add GUI (upload image)
Save output automatically
Multiple sketch styles
