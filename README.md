# textclassification-neural-net

## Dependencies

The project requires the following Python libraries:

- numpy
- pandas
- matplotlib
- scikit-learn
- imbalanced-learn
- tensorflow

These can be installed using `pip install -r requirements.txt`.

## Dataset

The dataset used in this project is the Diabetes dataset. Ensure the dataset file `diabetes.csv` is placed in the project directory.

## Model

The model is a simple feedforward neural network with the following architecture:

- Input layer
- Two hidden layers with 16 neurons each and ReLU activation
- Output layer with 1 neuron and sigmoid activation

The model is trained using the Adam optimizer and binary crossentropy loss.

## Results

The results of the model training, including accuracy and loss, will be displayed in the console output. Additional plots showing the distribution of features for diabetic and non-diabetic patients are also generated.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
