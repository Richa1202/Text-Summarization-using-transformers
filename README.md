# Text Summarization using Transformers

A deep learning project that implements a Transformer based sequence to sequence model for abstractive text summarization using TensorFlow.

## Environment Setup

### Requirements

- TensorFlow with CUDA support
- NumPy
- Pandas

Install dependencies:
```bash
pip install -r requirements.txt
```

### Dependencies

```
tensorflow[and-cuda]
numpy
pandas
```

## Current Status

**Note**: This model is currently generating incorrect summaries. The model capacity is limited due to hardware constraints (no GPU available for testing). The current configuration uses:

- 2 encoder/decoder layers
- d_model = 64
- 4 attention heads
- 5 training epochs

These limited hyperparameters may not be sufficient for the model to learn meaningful patterns for abstractive summarization.

## Future Improvements

- Increase model capacity (more layers, larger embedding dimensions)
- Train on larger datasets for longer epochs
- Implement beam search for better inference
- Add evaluation metrics (ROUGE, BLEU)
- Experiment with different architectures and hyperparameters
- Use pre-trained models (BERT, GPT) as encoders

## References

- "Attention Is All You Need" - Vaswani et al. (2017)
- TensorFlow Transformer Tutorial
- Inshorts Dataset

## License

This project is for educational purposes.
