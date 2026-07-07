# Rock-Paper-Scissor Recognition

In this project I used teachable machine and colab to recognize hand gestures representing **Rock**, **Paper**, or **Scissors** from an input image.

## How to Use

1. Make sure the following files are in the same directory as your Python script:
   - `keras_model.h5`
   - `labels.txt`
   - Your input image

2. Replace the image path in the code with the path to the image you want to classify.

### Example

```python
# Replace this with the path to your image
image = Image.open("<image.png>").convert("RGB")
