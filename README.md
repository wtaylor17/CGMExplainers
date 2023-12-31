# CGMExplainers
Implementation of "Causal Generative Explainers using Counterfactual Inference".

The Morpho-MNIST data used in the paper can be downloaded [here](https://drive.google.com/drive/folders/1M01WUONnrHZ3jIBKEWYX5eE9B0dd4pry?usp=sharing).

Models can be downloaded [here](https://drive.google.com/drive/folders/1jj5w5vkm-ufpLfqfj5tALkVPzSDyuM5j?usp=sharing). Once downloaded, this is what you should pass as the `--model-dir` argument to many scripts.

Precomputed shap values can be downloaded [here](https://drive.google.com/drive/folders/1BTdGfRNIaLj7TQ7wygumB4Uz35q5APAK?usp=sharing) for the `--shap-value-dir` argument to certain scripts.

Precomputed metrics for IM1/IM2/oracle scores can be downloaded [here](https://drive.google.com/drive/folders/1S90PgMwHxJ5eham4JQDOvOumLz87Yf0I?usp=sharing). These are passed as the `--metrics-csv` argument to appropriate scripts.

If any of the above links do not work, please reach out to me at wl647481@dal.ca

## Notes on `--data-dir`

Sometimes it expects the directory of precomputed CFs rather than the directory with the whole dataset. The scripts where this is the case are `image_shap_evolution.py`, `mnist_cf_comparisons.py`, and `contrastive_evolution.py`.