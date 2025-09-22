# 🐄🐃 Cattle & Buffalo Breed Identifier — Team IdeaMakers

This is a simple website to identify whether an uploaded image is of a **cattle** or **buffalo**, and also suggest its **breed**.

## 🚀 Features
- Upload an image of the animal.
- Upload reference images with labels (e.g., `Cattle - Gir`, `Buffalo - Murrah`).
- The site compares the uploaded image with references using **template matching** (no machine learning model required).
- Returns the closest match and classification.

## 🛠️ How it works
1. User uploads a target animal photo.
2. User uploads multiple reference images (with breed labels).
3. The site resizes and compares pixel data (MSE similarity).
4. Displays the best match and whether it’s cattle or buffalo.

## 👥 Team
**IdeaMakers**

## 📄 License
This project is licensed under the [MIT License](LICENSE).
