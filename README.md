# Multilayer Perceptron for Images
This project uses three **Multilayer Perceptron (MLP) models** trained on the **MNIST dataset** with different activation functions: 
1. Rectified Linear Unit (ReLU)
2. LeakyReLU 
3. Sigmoid

### Objective

The goal is to evaluate how activation functions influence convergence, accuracy, and model behavior. Activation functions are critical for deep learning because they introduce nonlinearity, enabling models to learn complex representations (Foster, 2022). The base code for this assignment was adapted from the official GitHub repository accompanying the textbook (Foster, 2022). I used this code to build and train the models and obtained the reported accuracy and loss results.

### Results

The results indicate that ReLU and LeakyReLU are generally preferred activation functions for image-based MLPs, but in this project, all models produced lower-than-expected accuracies. Using the provided code facilitated model building and training, and the results highlight the importance of proper hyperparameter tuning and preprocessing. ReLU remains a simple and effective choice, while LeakyReLU can provide additional stability, and Sigmoid is generally less suitable for hidden layers.

### References

[Foster, D. (2022). Generative deep learning (2nd ed.). O’Reilly Media.](https://reader2.yuzu.com/reader/books/9781098134143/epubcfi/6/2[%3Bvnd.vst.idref%3Dcover]!/4/2/2%4054:75)

[Foster, D. (2022). Code for multilayer perceptron assignment. GitHub.](https://github.com/davidADSP/Generative_Deep_Learning_2nd_Edition/blob/main/notebooks/02_deeplearning/01_mlp/mlp.ipynb?short_path=565a3ab) 

[OpenAI. (2025). ChatGPT (Aug 31 version) [Large language model].](https://chat.openai.com/chat)

### Resources/Tools Used:

1. **Google Colab** and Gemini for Debugging and executing the code.
2. **ChatGPT** for generating initial code.
3. **Microsoft Word** Document for documentation 
