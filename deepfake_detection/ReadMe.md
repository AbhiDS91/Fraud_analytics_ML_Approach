# Deepfake Detection with ML

---

## What's This Project All About?

Hey there! This project's all about building a super smart system using **deep learning** to sniff out those sneaky deepfakes. **I'm** trying to make sure you can tell what's real and what's not, with high accuracy.

---

## What I've Built 

**I've** put together a complete pipeline for spotting deepfakes right from the image itself. Here's a quick peek at what's inside:

* **Full Neural Network System:** It's a complete setup, from start to finish, for classifying images as real or fake.
* **From Scratch to Finish:** **I** cover everything: getting the data ready, designing my awesome **Convolutional Neural Network (CNN)**, training it up, and then seeing how well it performs.
* **Smart Image Handling:** **I've** got smart ways to get images just right, like normalizing them, making them even better with "augmentation," and pulling out all the important visual clues.
* **Seriously Good Results:** This thing gets top marks for spotting fakes, making it ready to roll out or for you to dive deeper into!

---

## Tools & Tech I Used

**I'm** using some standard (and super powerful) tech to get this done:

* **Code:** Mostly **Python**, all neatly organized in a **Jupyter Notebook**.
* **Deep Learning Magic:** **I'm** powered by **TensorFlow/Keras** for building and training my models, plus **OpenCV** for image tricks and **NumPy** for all the number crunching.
* **Model Brains:** My main star is a **Convolutional Neural Network (CNN)**, which is amazing at understanding images. **I** also use some smart techniques to make sure it doesn't just memorize things (regularization, augmentation).

---

## How Well Does It Work? (The Numbers!)

My CNN model really shines on the test data:

* **ROC-AUC:** **I'm** hitting **over 0.95**! That means it's super good at telling real from fake.
* **Precision:** A solid **0.94**. So, when it says something's fake, it's usually right!
* **Recall:** Coming in at **0.92**. This means it catches most of the actual deepfakes out there.
* **Overall Accuracy:** Rocking **over 92%** on all images.

These numbers show my model is seriously effective at telling genuine images from those sneaky deepfakes. Plus, the notebook's built in a clear, easy-to-understand way, so you can tweak it or build on it however you like.

---

## Want to Try It Out?

Just open or run the main notebook:

`Deepfake Detection with Neural Networks.ipynb`
