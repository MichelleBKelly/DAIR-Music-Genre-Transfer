# DAIR-Music-Genre-Transfer
Exploring the use of machine learning and music information retrieval for instrument-specific symbolic music genre transfer.

## Repository Structure
```text
├── model/                    # VAE, LSTM encoder/decoder, adversarial classifier
├── dataset/                  # Data loading, piano roll processing
├── losses.py                 # VAE and adversarial loss functions
├── main.py                   # Training script
├── remi_eval.py              # Inference / evaluation script
├── opts.py                   # Argument parsing and experiment configuration
├── requirements.txt          # Python dependencies
└── README.md                 # Documentation
```

## My Contributions
- Implementing the LSTM-based VAE encoder and decoder for sequential musical feature representation.
- Refining VAE loss functions, KL divergence behavior, and reshaping logic for stable training.
- Updating and improving the adversarial genre classifier for better latent disentanglement.
- Adding evaluation utilities (remi_eval.py) and improving training configuration options.
- Debugging and refactoring core components, improving sequence handling, reconstruction accuracy, and overall model stability.
