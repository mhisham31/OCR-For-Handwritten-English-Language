# OCR-For-Handwritten-English-Language

- This OCR project utilizes **TrOCR** as its model for handwritten character recognition. It can provide a higher accuracy rate compared to other CRNN models like PaddleOCR (after sufficient training).
- We observed that our pre-trained model had a **higher accuracy** compared to PaddleOCR when tested on a custom dataset while needing **lesser epochs of training** comparatively. 
- Our model is **trained on a small subset of the IAM Forms dataset**. A number of pre-processing techniques were applied to transform the data for use in our model. Since the data was presented in paragraphs of text, techniques were employed to split these paragraphs into sentences, and then words.
