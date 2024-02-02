# Transformer-based-Language-Model-GPT2

This notebook runs on Google Colab.
Codes from A Comprehensive Guide to Build Your Own Language Model in Python - (https://medium.com/analytics-vidhya/a-comprehensive-guide-to-build-your-own-language-model-in-python-5141b3917d6d)

Use the OpenAI GPT-2 language model (based on Transformers) to:
Generate text sequences based on seed texts
Convert text sequences into numerical representations

### I kept getting multiple erros so I am still working on it.

# Language Model Builder in Python

## Overview

This GitHub repository contains a comprehensive guide and code samples for building your own language model in Python. The guide covers various aspects of language models, starting from basic concepts to more advanced techniques, using both traditional statistical methods and neural networks.

The guide is based on an article titled "A Comprehensive Guide to Build your own Language Model in Python!" written by Mohd Sanad Zaki Rizvi and published on Analytics Vidhya on August 7, 2019.

## Key Features

1. **Introduction to Language Models in NLP:**
   - Defines the purpose of language models in natural language processing.
   - Highlights the importance of language models in tasks like machine translation.

2. **Types of Language Models:**
   - Discusses two primary types: Statistical Language Models and Neural Language Models.
   - Explains the use of traditional techniques like N-grams and newer approaches involving neural networks.

3. **Building an N-gram Language Model:**
   - Demonstrates the construction of a basic language model using trigrams on the Reuters corpus.
   - Discusses the limitations of N-gram models.

4. **Building a Neural Language Model:**
   - Introduces deep learning for language modeling, focusing on character-level models.
   - Provides code snippets for encoding sequences, creating training sets, and building a neural language model using Keras.

5. **Natural Language Generation using OpenAI’s GPT-2:**
   - Explores the capabilities of OpenAI's GPT-2 for sentence completion and paragraph generation.
   - Demonstrates the model's sensitivity to input text and its ability to generate coherent paragraphs.

6. **Conditional Text Generation using GPT-2:**
   - Shows how to use GPT-2 for conditional text generation, predicting the next word in a sentence.
   - Provides examples of generating entire paragraphs based on input text.

## Getting Started

Follow the steps outlined in the guide to understand and implement language models. The code samples are written in Python and use popular libraries such as NLTK and Keras. Additionally, instructions for setting up PyTorch-Transformers for GPT-2 usage are provided.

## Contributing

Contributions are welcome! If you have improvements, suggestions, or additional examples, feel free to open an issue or submit a pull request.

## Acknowledgments

- Mohd Sanad Zaki Rizvi for the original article on Analytics Vidhya.
- OpenAI for the development of GPT-2 and PyTorch-Transformers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
