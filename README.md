# Rock-Paper-Scissor Recognition

A simple image‑classification project that recognizes hand gestures for **Rock**, **Paper**, and **Scissor** using a trained Keras model.

## Project Overview

This model was trained on images of hand gestures representing the three classes:

- **Rock**
- **Paper**
- **Scissor**

Each class contains multiple sample images captured using webcam or uploaded manually during training.  
The model outputs the predicted class along with a confidence score.

---

## How to Use

1. Make sure the following files are in the same directory as your Python script:
   - `keras_model.h5`
   - `labels.txt`
   - Your input image

2. Replace the image path in the code with the path to your image:

    ```python
    # Replace this with the path to your image
    image = Image.open("<image.png>").convert("RGB")
    ```

3. Run the script to classify the gesture.

---

## Example Output

When you run the prediction script, you will see something like:

<img width="542" height="78" alt="Screenshot 2026-07-09 190017" src="https://github.com/user-attachments/assets/dfbcaf20-b57f-4c19-8636-67f23762b993" />


This means the model recognized the gesture as **Scissor** with about **90% confidence**.

---

## Training Preview

The model was trained using a simple interface where images were collected for each class:

- Rock (25 images)
- Paper (27 images)
- Scissor (29 images)

<img width="1341" height="912" alt="Screenshot 2026-07-09 190036" src="https://github.com/user-attachments/assets/dde744b6-3fc9-4666-b932-fc11ab9ebfa7" />
