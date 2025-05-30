# 👗 Fashion Sphere

**Fashion Sphere** is a cutting-edge AI-powered fashion platform that revolutionizes the shopping experience by combining computer vision, deep learning, and interactive tools. It offers image-based product search, virtual try-on, personalized recommendations, and more — all built with a seamless Flask backend and MySQL database.

---

## 🚀 Features

### 🔍 1. Image-Based Search (ResNet-50)
Users can upload an image, and the system identifies visually similar fashion items using a deep learning model based on **ResNet-50**.

### 🧥 2. Virtual Try-On (Live Camera Input)
Try clothes virtually using **OpenCV** with real-time camera feed. This allows users to preview how clothing items might look on them.

### 🎯 3. Content-Based Filtering
Recommendation engine that suggests fashion items based on visual similarity and content features extracted from product data.

### 📏 4. Body Size Estimation
Upload a body image to get a personalized size recommendation. This helps in reducing size-related returns.

### 🤖 5. Fashion-Focused Chatbot
An intelligent assistant powered by **Google Gemini**, trained to answer fashion queries, suggest outfits, or assist with shopping help.

---

## 🧾 Note on Pretrained `.pkl` Files

To run the **content-based** and **image-based** search features in **Fashion Sphere**, you'll need specific `.pkl` files that store extracted features and model data.

These files are generated in two independent GitHub repositories:

1. **[Image_Based_Search](https://github.com/SiddhiPatwardhan/Image_Based_Search)**  
   - Implements the **image-based search** functionality using ResNet-50.  
   - Contains the dataset and script to generate pkl files.

2. **[Fashion_Recommendaation_System](https://github.com/SiddhiPatwardhan/Fashion_Recommendation_System)**  
   - Implements the **content-based recommendation system**.  
   - Contains product metadata and script to generate pkl files.

Once you generate the `.pkl` files in the respective projects, copy them into the required directories in the **Fashion Sphere** main project to enable the corresponding features.

---

## 🛠️ Tech Stack

| Component        | Technology              |
|------------------|--------------------------|
| Backend          | Flask (Python)           |
| Database         | MySQL                    |
| Computer Vision  | OpenCV, ResNet-50        |
| AI Assistant     | Google Gemini API        |
| Recommendation   | Content-Based Filtering  |

---

