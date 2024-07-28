# LayoutLM Token Classification for Medical QA

This project involves using the LayoutLM model for token classification on a dataset of medical questions and answers. 
The goal is to classify tokens in text for various downstream tasks.

## Dataset

The [MedQuAD dataset](https://www.kaggle.com/datasets/jpmiller/layoutlm?select=medquad.csv) consists of questions, answers, sources, and focus areas related to medical topics. It is loaded from a CSV file.

## Prerequisites

- Python 
- PyTorch
- Hugging Face Transformers
- Datasets
- Pandas
- Weights & Biases (for tracking experiments)

## Usage

1. Load the dataset

2. Preprocess the data by removing rows with NaN values

3. Initialize the tokenizer

4. Convert the dataset to a Hugging Face Dataset

5. Tokenize and format the dataset

6. Initialize the model

7. Set up training arguments and initialize the Trainer

8. Train the model

9. Evaluate the model

10. Make predictions on new data
    

## Results

The model achieves a very low validation loss during training, indicating good performance on the token classification task.

## References

- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [LayoutLM](https://github.com/microsoft/unilm/tree/master/layoutlm)

## License

This project is licensed under the MIT License.
