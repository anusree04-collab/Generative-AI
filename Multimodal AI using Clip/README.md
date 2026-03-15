Multimodal AI using CLIP

---

Project Overview

This project demonstrates a multimodal artificial intelligence model that connects images and text using the CLIP developed by OpenAI.

The model compares an input image with multiple text descriptions and predicts which text best matches the image.

---

Objective

The goal of this project is to understand how multimodal models work by combining:

- Image data
- Text data

The CLIP model converts both images and text into embeddings and calculates similarity between them.

---

Technologies Used

- Python
- PyTorch
- Transformers Library
- PIL (Python Imaging Library)
- Google Colab

---

Project Workflow

1. Upload an image (example: dog.jpg)
2. Provide text labels such as:
   - "a dog"
   - "a cat"
   - "a car"
3. The CLIP model converts the image and text into embeddings
4. The model calculates similarity scores
5. The highest probability indicates the correct label

---

Example Output

Input Image: dog.jpg

Labels tested:

- a dog
- a cat
- a car

Prediction:

a dog → 98.53%
a cat → 0.47%
a car → 1.00%

---


How to Run

1. Open the notebook in Google Colab
2. Upload an image
3. Run the cells sequentially
4. The model will predict the matching text label

---

Project implemented as part of Generative AI learning and experimentation.
