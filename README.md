# CIFAR-10 Image Classification Using CNNs
## Key Features

1. **Dataset**: Uses the CIFAR-10 dataset containing images across 10 classes:
   - Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

2. **Model Architecture**: Implements a CNN model with:
   - Conv2D layers for feature extraction
   - MaxPooling layers for dimensionality reduction
   - BatchNormalization for stable training
   - Dropout layers to prevent overfitting
   - Dense layers for classification

3. **Data Augmentation**: Uses ImageDataGenerator to artificially expand the training dataset

4. **Evaluation**: Includes model evaluation metrics like:
   - Confusion matrix
   - Classification report
   - Accuracy measurement

## Notebook Structure

1. **Data Loading**: Downloads and loads the CIFAR-10 dataset
2. **Data Visualization**: Shows sample images from each class
3. **Data Preprocessing**: Normalizes pixel values and converts labels to one-hot encoding
4. **Model Building**: Constructs the CNN architecture
5. **Model Training**: Trains the model with early stopping
6. **Model Evaluation**: Assesses performance on test data

## Results

The notebook achieves 88% accuracy on the test set, demonstrating the effectiveness of CNNs for image classification tasks.

## How to Use

1. Run the notebook cells sequentially
2. The model will train and output accuracy metrics
3. You can modify the architecture or hyperparameters to experiment with different configurations

The notebook provides a solid foundation for image classification tasks and can be extended to other datasets or more complex architectures.

For the full implementation details and code, please refer to the notebook content.
