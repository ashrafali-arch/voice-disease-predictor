# Voice Disease Predictor

A machine learning project to predict diseases using speech features such as MFCCs (Mel Frequency Cepstral Coefficients) and deep learning models.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Voice Disease Predictor analyzes voice recordings to detect the presence of diseases or vocal disorders. It uses feature extraction techniques like MFCC and applies deep learning models for classification.

## Features

- Extracts MFCC and other speech features from audio files
- Deep learning-based classification (e.g., CNN, RNN)
- Easy-to-use interface (CLI or web)
- Modular and extensible

## Demo

Coming soon!

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ashrafali-arch/voice-disease-predictor.git
    cd voice-disease-predictor
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your dataset (see `data/` or instructions in the code).
2. Train the model:
    ```bash
    python main.py --train
    ```
3. Predict using a new audio file:
    ```bash
    python main.py --predict --file path/to/audio.wav
    ```

## Project Structure

```
voice-disease-predictor/
│
├── main.py                # Main entry point for training and prediction
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
├── model/                 # Model architecture and weights
├── data/                  # Dataset and feature files
├── utils/                 # Utility scripts (feature extraction, etc.)
├── .gitignore             # Files to ignore in git
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)
