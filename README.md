# LSTM-Based Next Word Prediction Model

## Overview
This project implements a Next Word Prediction model using an LSTM-based Recurrent Neural Network (RNN). The dataset used is `shakespeare-hamlet` from the NLTK Gutenberg corpus. The model is trained to predict the next word in a given sentence based on Shakespearean text.

## Dataset
The dataset is sourced from the NLTK library:
- `shakespeare-hamlet` from the Gutenberg corpus.
- Preprocessing includes tokenization, sequence generation, and vectorization.

## Features
- Uses LSTM-based RNN for next-word prediction.
- Text data preprocessing with NLTK and TensorFlow/Keras.
- Trained on Shakespeare's Hamlet text.
- Supports user input for predicting the next word.

## Installation
To run this project, install the required dependencies:

```bash
pip install nltk tensorflow keras numpy
```

Additionally, ensure that the NLTK dataset is downloaded:

```python
import nltk
nltk.download('gutenberg')
nltk.download('punkt')
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lstm-next-word-prediction.git
   cd lstm-next-word-prediction
   ```

## Model Architecture
- **Embedding Layer**: Converts words into dense vectors.
- **LSTM Layers**: Captures sequential dependencies.
- **Dense Layer**: Outputs probabilities for the next word.

## Example Output
**Input:** "To be or not to"

**Predicted Next Word:** "be"

## Future Improvements
- Train on larger Shakespearean datasets.
- Implement beam search for better predictions.
- Deploy as an interactive web app.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.

