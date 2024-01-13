# Goat Detector: Messi vs. Cristiano Ronaldo Classifier

## Project Overview
This project comprises two Jupyter notebooks that use machine learning to classify images as either featuring the football players Messi or Cristiano Ronaldo. The project utilizes the fastai/fastbook libraries for image processing and classification.

### `goat_detector_training.ipynb`
This notebook focuses on training a model to classify images. It includes steps for loading images, preparing them, and then feeding them to a pre-trained machine learning model for fine-tuning.

### `goat_detector_inference.ipynb`
This notebook is designed for inference. It loads the fine-tuned model and creates a Gradio interface, allowing users to test the model on new data interactively.

## Installation
To use these notebooks, you need to install certain Python libraries. You can install the necessary dependencies via pip:

```bash
pip install fastai fastbook gradio
```

## Usage
1. Training the Model
2. Open goat_detector_training.ipynb in a Jupyter environment.
Follow the instructions in the notebook to train the model. This involves loading the dataset, setting up the model, and running the training process.

## Testing the Model
1. Open goat_detector_inference.ipynb in a Jupyter environment.
2. Run the cells to load the trained model and set up the Gradio interface.
3. Use the Gradio interface to upload new images and see the model's predictions.
   
## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

### License
This project is licensed under the Apache 2.0 License - see the LICENSE.md file for details.

### Acknowledgements
Fast.ai for the excellent library and resources.
Gradio for the interactive interface capabilities.