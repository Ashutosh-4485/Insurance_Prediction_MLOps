

## 💡 Project Overview

This project demonstrates a complete end-to-end **Machine Learning pipeline** built with a strong MLOps foundation. The key components include:

* ✅ **Manual ML Pipeline in Python**
  Implemented from scratch including:

  * Data Ingestion
  * Data Validation
  * Feature Engineering
  * Model Training
  * Model Evaluation

* 🐳 **Dockerized Workflow**
  The entire pipeline and serving app are containerized using Docker for easy deployment and environment consistency.

* ☁️ **AWS Integration**

  * Trained model and artifacts are stored in an **Amazon S3 bucket**.
  * A simple **Flask-based UI application** is hosted on an **EC2 instance**, serving real-time predictions.

* 🔁 **Model Serving**
  The Flask app is integrated with the trained model and exposes endpoints for prediction, enabling smooth user interaction.

* 🚀 **CI/CD Pipeline**
  Configured **GitHub Actions** for continuous integration and deployment:

  * Automatically runs tests and builds Docker images.
  * Deploys updated code to the EC2 instance on push.

---

Let me know if you also want to include a section for setup instructions or architecture diagram.
