# Basic Transformer and LSTM For next character prediction

This repository contains a minimal character-level Transformer (decoder-only) and LSTM implemented in JAX/Flax for next-character prediction. 

Repository structure
--------------------

Top-level layout:

- `LSTM.ipynb` - Primary Jupyter notebook used for experimenting, training and generation for the LSTM model. The notebook contains data loading, model initialization, hyperparameter tuning and optimization, training loop, evaluation on test set, and a JITted token generator cell.
- `LSTM_BO_pics/` - Contains pictures of plotted graphs in the LSTM.ipynb file.
- `LSTM_utils/` - Contains stored checkpoints and hyperparameters from running the LSTM.ipynb file.
- `transformer.ipynb` - Primary Jupyter notebook used for experimenting, training and generation for the transformer model. The notebook contains data loading, model initialization, hyperparameter tuning and optimization, training loop, and evaluation on test set.
- `transformer_utils/` - Contains stored checkpoints from running the transformer.ipynb file.
- `requirements.txt` - Contains the python libraries that needs to be installed for this project.
- `data/` - Contains the train and test data used for this assingment


