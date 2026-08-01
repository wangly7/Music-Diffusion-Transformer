# Music Transformer for Symbolic Music Generation

A PyTorch implementation of a Transformer-based model for symbolic music generation using the JSB Chorales dataset.

## Highlights

- Transformer decoder for autoregressive music generation
- Trained on the JSB Chorales dataset
- MIDI tokenization and sequence modeling
- Generates symbolic music in MIDI format

## Model

- Framework: PyTorch
- Architecture: Transformer Decoder
- Dataset: JSB Chorales
- Loss: Cross Entropy
- Optimizer: AdamW

## Results

The model learns harmonic and temporal dependencies in four-part chorales and generates coherent symbolic music sequences.

## Run

```bash
pip install -r requirements.txt

jupyter notebook "JSB Chorales.ipynb"
```

## Repository

```
├── JSB Chorales.ipynb
├── checkpoints/
├── generated/
└── README.md
```

## References

- Attention Is All You Need
- Music Transformer
- JSB Chorales Dataset