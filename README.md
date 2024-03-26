# Paraphrase Generator with PEGASUS Transformer 🔄

Welcome to the Paraphrase Generator! This tool utilizes the power of Google PEGASUS pretrained transformers to generate paraphrases of sentences while maintaining their original meaning.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Examples](#examples)

## Introduction
Do you need variations of a sentence without altering its essence? Look no further! This Paraphrase Generator is designed to assist you in generating paraphrased versions of your sentences using state-of-the-art language models.

## Features
- **Paraphrase Generation**: Generate alternative versions of input sentences while preserving their original meaning.
- **PEGASUS Transformer**: Utilizes Google's PEGASUS pretrained transformers, known for their high-quality paraphrase generation.
- **Customizable Length**: Adjust the length of the generated paraphrases to suit your needs.


## Usage
1. Import the `ParaphraseGenerator` class into your Python script.
2. Create an instance of `ParaphraseGenerator`.
3. Call the `paraphrase` method with your desired sentence as input.

```python
- Input: "The quick brown fox jumps over the lazy dog."

Output:
"The speedy brown fox leaps over the lethargic dog."
"The fast brown fox jumps over the lazy dog."
"The quick brown fox jumps over the sluggish dog."
Input: "I love coding with Python."

- Input: "I love coding with Python."
Output:
"I adore programming with Python."
"I enjoy coding using Python."
"Python coding is something I love."
```
