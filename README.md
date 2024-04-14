# Data Preprocessing with Keras Data API and scikit-learn

This repository provides examples and code snippets for data preprocessing using the Keras Data API and scikit-learn.

## Overview

Data preprocessing is a crucial step in the machine learning pipeline, as it involves transforming raw data into a format suitable for training machine learning models. The Keras Data API offers powerful tools for loading and manipulating data within the TensorFlow ecosystem, while scikit-learn provides a wide range of traditional preprocessing techniques.

![image](https://github.com/guina12/deep_learning_preprocessing_data/assets/115325442/6aebf9a4-14cd-4195-8ba3-ff6ac99a8d61)

![image](https://github.com/guina12/deep_learning_preprocessing_data/assets/115325442/fcbd4f18-7f62-479f-99de-f1d2c8351e38)

## Usage

You can explore the examples provided in each directory to understand how to perform common data preprocessing tasks using both the Keras Data API and scikit-learn. Each example includes detailed comments and explanations to guide you through the process.


### Parameters
- `filepaths`: List of file paths or a file pattern to read CSV files from.
- `repeat`: Number of times to repeat each file.
- `n_readers`: Number of parallel readers to use.
- `n_read_threads`: Number of threads for parallel reading.
- `shuffle_buffer_size`: Size of the buffer for shuffling.
- `n_parse_threads`: Number of threads for parsing.
- `batch_size`: Batch size.
- example:
- dataset = csv_reader_dataset(filepaths=["data/file1.csv", "data/file2.csv"], 
                             repeat=3, 
                             batch_size=64)


## Requirements

- TensorFlow and Keras
- scikit-learn
- NumPy

## Contributing

Contributions to improve and expand the repository are welcome! If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request.

