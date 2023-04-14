# CNN-Model-for-CIFAR-10-Image-Classification-using-PyTorch
This repo defines a Convolutional Neural Network (CNN) to classify images of the CIFAR-10 dataset. The code loads the dataset, preprocesses it, visualizes some examples, and trains the model.

The code is organized into sections, where each section corresponds to a different step in the process. There are comments throughout the code that explain what each section does:

### 1.Load libraries:
This section imports the required Python libraries.

### 2.Load dataset: 
This section loads the CIFAR-10 dataset and preprocesses it. The dataset is split into training, validation, and test sets, and each set is loaded into a separate data loader. The data loader allows the model to load the data in batches.

### 3.Visualize data:
This section defines a function that shows a random image from the dataset and its corresponding label.

### 4.Define CNN model:
This section defines the CNN model using the PyTorch nn.Module class. The model has two convolutional layers, two fully connected layers, and an output layer. The ReLU activation function is used after each layer.

### 5.Train model:
This section trains the model using the training set and evaluates it on the validation set. The training loop runs for a fixed number of epochs, and the model's performance is evaluated after each epoch. The performance metrics include the loss, accuracy, confusion matrix, and classification report.
