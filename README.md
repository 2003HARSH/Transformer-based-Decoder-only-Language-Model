# Transformer-based (Decoder-only) Language Model from Scratch

This repository contains the implementation of a language model built from scratch using PyTorch. The model leverages a transformer-based (decoder-only) architecture, similar to GPT.

## Model Architecture

- **Model Parameters**: 14.26 million
- **Batch Size**: 256
- **Block Size**: 64
- **Max Iterations**: 10,000
- **Learning Rate**: 3e-4
- **Evaluation Iterations**: 100
- **Embedding Size**: 384
- **Number of Layers**: 12
- **Number of Attention Heads**: 8
- **Dropout Rate**: 0.2
- **Context Window**: 64 characters
- **Tokenizer**: Character-level
- **Vocublary Size**: 145
- **Training Data**: 2GB of open source textual data 

## Why Build a Language Model from Scratch?

In an era where we can easily import state-of-the-art language models (LLMs) like GPT, BERT, or T5, you might wonder why build one from scratch. Here’s why:

1. **Deep Understanding**: Constructing a language model from scratch provides an in-depth understanding of the underlying mechanics of transformer architectures. This knowledge is crucial for debugging, fine-tuning, and optimizing models for specific tasks.
2. **Customization**: Off-the-shelf models are often generalized to handle a broad range of tasks. Building a custom model allows for tailored adjustments, ensuring optimal performance for specialized applications.
3. **Innovation**: By exploring the fundamental building blocks, we can experiment with novel architectures and techniques, potentially leading to innovative solutions and improvements beyond current state-of-the-art models.
4. **Educational Value**: The process of designing and implementing a model from scratch is an invaluable learning experience. It sharpens problem-solving skills, deepens expertise in machine learning, and enhances coding proficiency.
5. **Performance Optimization**: Understanding the intricacies of the model enables us to optimize its performance, memory usage, and speed, which is particularly beneficial for deploying models in resource-constrained environments.
6. **Transparency**: Building from scratch ensures complete transparency and control over the model's architecture, data handling, and training process, which is essential for developing ethical and trustworthy AI solutions.

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch 1.8.1+

### Installation

Clone the repository:

```bash
git clone https://github.com/2003HARSH/tinyGPT.git
cd tinyGPT
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Final Thoughts

Although this model may not yet match the capabilities of the leading LLMs out there, the experience has been incredibly informative. It's particularly rewarding to see the character-level tokenizer accurately form meaningful words—a significant achievement in itself. Given enough data and computational power, this model has the potential to perform exceptionally well.

Feel free to contribute to the project or use it as a learning tool for understanding transformer architectures and language model training from scratch.

## Contributing

We welcome contributions to improve the model, add new features, or fix bugs. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

