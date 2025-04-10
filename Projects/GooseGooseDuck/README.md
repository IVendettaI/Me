This trained model has 2 classes

Goose - 1

Duck - 0

instruction:

Now we work with file Code

1. Preprocessing

Let's say you have a photo "img" you need to use Preprocessing_code() function below to preprocess the image. This code works with paths to root folders where images are stored. We need images 299х299

2. Checking the correctness

Afterwards you can use img_check function to check if the images are processed correctly.

Example:

![изображение](https://github.com/user-attachments/assets/73f77c01-dd87-40bd-8c70-5468771588c0)

3.Now you need to load the model, in the code there is a function for_keras and for_PyTorch

The model can recognize not only ducks and geese, but also ducklings and goslings, and can also recognize drawings and rubber ducks.

you can chek it with samples in folder Samples
