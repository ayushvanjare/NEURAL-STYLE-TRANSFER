# NEURAL-STYLE-TRANSFER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AYUSH VANJARE

*INTERN ID*: CTIS8057

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

---

## 📌 About the Project
This project implements a basic **Image Style Transfer** technique using **PyTorch**.

It combines:
- 🖼️ **Content Image** (structure)
- 🎨 **Style Image** (artistic style)

to generate a new stylized output image.

---

## ✨ Key Features
- 🖼️ Load and preprocess images  
- 🎨 Combine content and style  
- ⚡ Optimization using gradient descent  
- 🔥 Implemented using PyTorch tensors  
- 📊 Output visualization using Matplotlib  

---

## 🛠️ Tech Stack
- **Language:** Python 3  
- **Libraries:**  
  - PyTorch  
  - Torchvision  
  - PIL (Python Imaging Library)  
  - Matplotlib  

---

## 📁 Project Structure

📦 Image-Style-Transfer

┣ 📜 Task_3.ipynb

┣ 🖼️ content.jpeg

┣ 🎨 style.jpeg

┣ 🖼️ output.jpg

┗ 📜 README.md

---

## ⚙️ Setup & Installation

### 1️⃣ Install Dependencies

pip install torch torchvision pillow matplotlib

▶️ How It Works

Load content and style images

Resize and convert images to tensors

Initialize output image

Define loss function:

Content Loss

Style Loss

Optimize using Adam optimizer

Generate final stylized image

💻 Code Overview

Image loading using PIL

Transformations using Torchvision

Optimization using PyTorch

Visualization using Matplotlib

📊 Example Workflow

Content Image + Style Image → Optimization → Stylized Output

⚠️ Limitations

Basic implementation (not true neural style transfer)

Uses simple pixel-wise loss instead of feature-based loss

Output quality may be limited

Requires tuning for better results

🔮 Future Enhancements

🚀 Use VGG19 for feature extraction

🚀 Implement true Neural Style Transfer

🚀 Improve output quality

🚀 Add real-time style transfer

🚀 Build web app using Streamlit
