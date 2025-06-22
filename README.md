## Neural Style Transfer

*COMPANY*: CODTECH IT SOLUTIONS PVT.LTD

*NAME*: Manvit Mahesh Deshmukh

*INTERN ID*: CT12DL764

*DOMAIN*: Artificial intelligence.

*DURATION*: 12 weeks

*MENTOR*:  Neela Santhosh Kumar

# 🎨 Neural Style Transfer – CodTech Internship Task 3

This project is a beginner-friendly implementation of **Neural Style Transfer** using PyTorch and Google Colab. It was created as part of the **CodTech Artificial Intelligence Internship (Task 3)**. The goal of this task is to take two images — a **content image** and a **style image** — and generate a new image that retains the structure of the content image but appears as if it were painted in the artistic style of the style image.

---

## 📌 What is Neural Style Transfer?

**Neural Style Transfer** is a deep learning technique that blends the "content" of one image with the "style" of another. It was introduced in the paper *"A Neural Algorithm of Artistic Style"* by Gatys et al. (2015). The technique uses the feature maps extracted by a **pretrained convolutional neural network (CNN)** — typically VGG19 — to combine structural elements and artistic textures.

---

## 🖼️ Project Workflow

1. **Upload Two Images**  
   - A **Content Image** (e.g., a bird, landscape, or portrait).  
   - A **Style Image** (e.g., artwork, painting, or abstract texture).

2. **Load Pretrained Model**  
   - We use VGG19 from PyTorch’s `torchvision.models` as the base network.

3. **Extract Features**  
   - From content and style layers to calculate feature differences.

4. **Define Loss Functions**  
   - **Content Loss**: Measures how much the target image differs from the content.
   - **Style Loss**: Measures how much the target deviates from the texture of the style image (using Gram matrices).

5. **Optimize the Output Image**  
   - A randomly initialized image (starting from the content image) is updated using backpropagation until it resembles the desired blend of content and style.

6. **Display & Save Result**  
   - The final image is visualized and can optionally be saved.

---

## 🔧 Tools and Libraries Used

- **Python**
- **Google Colab**
- **PyTorch**
- **Torchvision**
- **PIL (Pillow)**
- **Matplotlib**

---

## 🚀 How to Use This Project

1. **Open Google Colab**  
   Visit: https://colab.research.google.com/

2. **Upload the `.ipynb` Notebook**

3. **Upload Two Images When Prompted**  
   - You will be asked to upload a content and style image via file upload.

4. **Run All Cells in Order**

5. **View the Result**  
   The stylized output will appear in your notebook after a few optimization steps.

---

## ✅ Example Output

If you use a bird image as content and a cyberpunk fantasy illustration as the style, the result will be a bird that looks painted in colorful brush strokes — vibrant, dreamlike, and artistic.

| Content Image | Style Image | Stylized Output |
|---------------|-------------|-----------------|
| ![Content](https://github.com/user-attachments/assets/ff7b3c8e-5657-4882-ad7d-8a2416118c68) | ![Style](https://github.com/user-attachments/assets/8a143432-7d8b-41d4-b1e2-124a92acd2b0) | ![Stylized](https://github.com/user-attachments/assets/4ae12985-54cd-4c9d-8bc1-f0c6ca60017b) |

(*Replace these with actual image links if hosted in your GitHub repo*)

---



- Automatically detects uploaded image names.
- Converts RGBA images to RGB to avoid tensor mismatch errors.
- Works on CPU or GPU (Colab automatically selects GPU if available).
- Pretrained VGG19 model is used for feature extraction.
- Simple code style written like a beginner for easy understanding.

---

## 📸 SCREENSHOTS

![Image](https://github.com/user-attachments/assets/36eea852-1ad5-4e1c-89ad-674bfbac1c08)
![Image](https://github.com/user-attachments/assets/fbba1438-5e01-4bc4-8005-62f82fb76753)
![Image](https://github.com/user-attachments/assets/bccffe1f-87c7-443d-9412-1fac36b515fb)
![Image](https://github.com/user-attachments/assets/7ee02025-66c2-4867-95a0-1fac80642dc5)
![Image](https://github.com/user-attachments/assets/cca24082-dbf3-4486-bf06-3d207193ae5f)
![Image](https://github.com/user-attachments/assets/8132d62b-588c-451e-a52e-3ec0b093df02)
![Image](https://github.com/user-attachments/assets/4985e7e2-174e-477b-bdc2-4bdfbdb41a6a)
![Image](https://github.com/user-attachments/assets/72f43297-e335-438d-8c83-abded4dc98a1)
![Image](https://github.com/user-attachments/assets/6a02360c-022d-4ed7-8a5c-564e787158d0)
![Image](https://github.com/user-attachments/assets/3fe3df73-ce9f-440d-a6a1-6be9c5950f45)
