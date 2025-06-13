🧠 Skin Cancer Detection using CNN (Benign vs Malignant)
This project is a deep learning-based skin cancer classification system that uses Convolutional Neural Networks (CNNs) to distinguish between benign and malignant skin lesions from dermatoscopic images. Built with PyTorch, it aims to assist early diagnosis of melanoma using automated image analysis.

📌 Project Overview
*Objective: Classify dermatoscopic images into benign or malignant.

*Model: Custom CNN / ResNet50 (pre-trained, fine-tuned).

*Dataset: 24,000+ images of size 224x224, split into training, validation, and testing sets.

*Framework: PyTorch

*Deployment goal (optional): Standalone tool that accepts an image input and returns a prediction for real-world use in clinics or telemedicine.

🗂️ Dataset
The dataset includes labeled images of skin moles:

*benign: non-cancerous moles

*malignant: cancerous lesions (melanoma)

⚠️ Note: Dataset preprocessing includes resizing to 224x224, normalization, and data augmentation to improve model generalization.

🚀 Features
*Image classification using CNNs

*Transfer learning with ResNet50

*Training, validation, and test metrics

*Visualization of training curves (loss, accuracy)

*Prediction on custom uploaded images

*(Planned) Simple user interface or API for real-time predictions

🧰 Technologies Used
*Python 3.9+

*PyTorch

*Torchvision

*Matplotlib

*NumPy

*Google Colab (for GPU training)

🧠 Future Improvements
Add a Flask or Streamlit web interface

Improve data augmentation strategies

Convert model to ONNX or TensorFlow Lite for mobile deployment

📄 License
MIT License. Feel free to use or modify this project for educational or research purposes.

🙋‍♂️ Author
Razvan – LinkedIn : https://www.linkedin.com/in/razvan-epure-841b05231 | Email : epr.razvan@gmail.com
