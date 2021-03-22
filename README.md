# Big 5 Demo
This project is a practical demonstration of the FastAI library.

We have built a model of the South African Big Five to identify which animal is in an upload picture. The project was build in the following steps.

1. Normal FastAI libraries  was imported.
2. Big Five images were downloaded from Migrosoft Bing. The images were uploaded in labelled folders.
3. Basic data cleanup was done and invalid images deleted.
4. The model was trained on Google Colab with one of its cloud GPUs.
5. After training it was evaluated.
6. Then the model was exported and the App was build using the model export file.

It is important to note that a GPU is not required on the App. The only step where the GPU is required is at the model training phase.