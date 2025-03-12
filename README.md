# Text Summarization Bot

## Overview

This project implements a Text Summarization Bot designed to generate concise summaries from input text. The bot is built using Python and leverages natural language processing techniques to extract key information, making lengthy texts more digestible.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Text Summarization**: Condenses lengthy documents into shorter summaries, retaining essential information.

- **Interactive Interface**: Provides an interactive interface for users to input text and receive summaries.

## Installation

To set up the Text Summarization Bot locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/akurapati1/textSummarizationBot.git
   cd textSummarizationBot
   ```


2. **Create a Virtual Environment**:

   ```bash
   python -m venv env
   ```


3. **Activate the Virtual Environment**:

   - On Windows:

     ```bash
     .\env\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source env/bin/activate
     ```

4. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```


## Usage

1. **Run the Application**:

   ```bash
   python app.py
   ```


2. **Interact with the Bot**:

   Open your web browser and navigate to `http://localhost:8501`.

   - **Input Text**: Enter the text you wish to summarize in the provided input field.

   - **Generate Summary**: Click the "Summarize" button to receive the condensed version of your input text.

## Dependencies

The project relies on the following Python packages:

- `streamlit`

- `nltk`

- `sumy`

- `scikit-learn`

These dependencies are listed in the `requirements.txt` file and can be installed using the provided installation instructions.

