# ML Python Library Mastery

Hands-on practice notebooks for mastering the core Python machine-learning and
data-science libraries, one library per notebook. Each follows the same rhythm:
a short **concept**, a runnable **demo**, and an **exercise** with its solution
right below. Every code cell is executed and verified to run end to end.

## Notebooks

| Notebook | Topic |
|----------|-------|
| `numpy_mastery.ipynb` | Arrays, broadcasting, ufuncs, linear algebra, vectorization |
| `pandas_mastery.ipynb` | Series/DataFrame, indexing, groupby, merge, reshaping, time series |
| `matplotlib_mastery.ipynb` | Figures/axes, chart types, subplots, styling, 3-D, dashboards |
| `seaborn_mastery.ipynb` | Statistical plots, distributions, categorical, regression, grids |
| `sklearn_mastery.ipynb` | Preprocessing, models, metrics, cross-validation, pipelines, tuning |
| `pytorch_mastery.ipynb` | Tensors, autograd, `nn.Module`, training loops, CNNs (MPS-aware) |
| `tensorflow_mastery.ipynb` | Tensors, Keras APIs, `fit`, `tf.data`, custom loops, callbacks |
| `transformers_mastery.ipynb` | Pipelines, tokenizers, embeddings, fine-tuning with `Trainer` |

## How to use

1. Open any notebook in Jupyter or VS Code.
2. Select the `k_tab` kernel (Python 3.12).
3. Run top to bottom. At each exercise, try the empty cell before viewing the solution.

## Environment

Verified against this stack (Python 3.12):

| Package | Version | Package | Version |
|---|---|---|---|
| numpy | 2.5.4 | torch | 2.15.0 |
| pandas | 3.1.0 | torchvision | 0.29.2 |
| matplotlib | 3.11.2 | torchaudio | 2.11.1 |
| seaborn | 0.13.2 | tensorflow | 2.21.0 |
| scipy | 1.18.1 | keras | 3.15.1 |
| scikit-learn | 1.9.1 | transformers | 5.22.1 |
| | | datasets | 5.1.0 |

The Transformers notebook downloads small models from the Hugging Face Hub on
first run (gpt2, bert-base-uncased, distilbert-base-uncased) and uses the
`rotten_tomatoes` dataset; an internet connection is needed the first time.
