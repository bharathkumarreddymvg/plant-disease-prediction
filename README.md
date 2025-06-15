# 🌿 Plant Disease Prediction – Potato Leaf Classifier

This project is a simple deep learning web app that helps detect diseases in potato plant leaves. It uses a trained Keras model for prediction, served through a FastAPI backend. A clean HTML/CSS interface is provided for users to upload images and view prediction results. The goal is to make it easier for farmers or researchers to identify common potato leaf diseases early.

You can watch a demo of the working application on GitHub at:
**[https://github.com/bharathkumarreddymvg/plant-disease-prediction](https://github.com/bharathkumarreddymvg/plant-disease-prediction)**


What the Project Includes

This app combines three main components:

1. **deep learning model** trained using TensorFlow/Keras. It can classify potato leaves into three categories: Early Blight, Late Blight, or Healthy.
2. **FastAPI backend**, which loads the model and processes image uploads to generate predictions.
3. **simple frontend interface** where users can upload leaf images and get immediate feedback on the disease status.



### How to Run It Locally

To get started, first clone the repository to your system and move into the project folder. You’ll need Python 3.9 or later installed.

Next, install the required packages using pip. All dependencies are listed in the `requirements.txt` file. Once installed, you can start the backend server using Uvicorn.

When the server is running, open your browser and go to 'http://localhost:8080/docs' to access the frontend and test the model.



### Technologies Used

* **TensorFlow / Keras** for training and saving the deep learning model
* **FastAPI** for building the backend API
* **Uvicorn** as the ASGI server
* **Pillow and NumPy** for image processing
* **HTML + Tailwind CSS** for the frontend interface

---

### Project Folder Overview

The project includes an `api` folder containing the FastAPI app, a `models` folder with the saved `.keras` file, and a `frontend` or `templates` folder for the HTML interface. All static assets like images or stylesheets are placed in the `static` folder if used.

---

### Author

This project was created by **Bharath Kumar Reddy**.
You can view more of my work on my GitHub profile:
**[https://github.com/bharathkumarreddymvg](https://github.com/bharathkumarreddymvg)**

---

### License

This project is licensed under the MIT License. Feel free to use, modify, and share it for your own work.



