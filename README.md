AI-Based Bone Fracture Detection and Analysis System

Project Overview
This system helps doctors and medical students detect bone fractures from X-ray images using artificial intelligence. The user uploads an X-ray image, and the AI instantly tells whether there is a fracture or not. It also shows a confidence score and a heatmap that highlights the suspected fracture area.

Models Used
The system uses two deep learning models: EfficientNetB0 (CNN) and Vision Transformer (ViT). Both models are compared, and the best one is used for predictions.

Main Features
- User registration and login with different roles (doctor, student, admin)
- X-ray image upload
- Fracture detection with confidence score
- Grad-CAM heatmap to highlight fracture area
- Prediction history saved in database
- Admin dashboard to manage users
- PDF report generation

Technology Stack
- Frontend: React.js
- Backend: FastAPI
- AI: TensorFlow, PyTorch
- Models: EfficientNetB0, Vision Transformer
- Database: PostgreSQL

Purpose
This is a Final Year Project that combines AI, full-stack development, and medical imaging to assist in faster and more accurate bone fracture diagnosis.
