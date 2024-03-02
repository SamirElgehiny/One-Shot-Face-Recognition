# One-Shot-Face-Recognition

This repository contains a face recognition model implemented using TensorFlow and OpenCV, specifically designed for one-shot learning scenarios. One-shot learning is a type of machine learning task where the model is trained to recognize objects or patterns from a single example. The model included in this repository is trained using one-shot learning techniques and can accurately recognize faces from just a single image. It utilizes a Siamese neural network architecture to learn embeddings for faces, enabling robust face recognition even with limited training data. The provided pre-trained model (`model.json` and `weights.h5`) can be easily integrated into applications requiring face recognition capabilities, especially in scenarios where only a few examples of each face are available.

## Getting Started

To get started with using the one-shot face recognition model, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your_username/OneShotFaceRecognition.git
```

2. Use the provided pre-trained model (`model.json` and `weights.h5`) for face recognition tasks. You can also modify the model or train your own on a custom dataset if needed.

3. Utilize the `img_to_encoding()` function to generate encodings for faces and the `who_is_it()` function to recognize faces in images.
