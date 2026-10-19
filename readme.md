# PyTorch Deep Learning Course

My notebooks and notes from Daniel Bourke's course [Learn PyTorch for Deep Learning](https://www.learnpytorch.io/), with my own comments.

## Notebooks

| Notebook | Topic |
|---|---|
| [00_pytorch_fundamentals](00_pytorch_fundamentals.ipynb) | Tensors and basic operations |
| [01_pytorch_workflow](01_pytorch_workflow.ipynb) | Linear regression on straight-line data , training loop, saving and loading |
| [02_pytorch_classification](02_pytorch_classification.ipynb) | Binary classification on circles data (make_circles), multi-class classification on blobs (make_blobs), non-linearity |
| [03_pytorch_computer_vision](03_pytorch_computer_vision.ipynb) | FashionMNIST, CNN (TinyVGG), confusion matrix |
| [04_pytorch_custom_datasets](04_pytorch_custom_datasets.ipynb) | Custom image dataset (pizza, steak, sushi), data augmentation |
| [08_pytorch_paper_replicating](08_pytorch_paper_replicating.ipynb) | Building a Vision Transformer (ViT) from the paper |
| [pytorch_2_intro](pytorch_2_intro.ipynb) | PyTorch 2.0 and `torch.compile()` (partial) |

## Notes

- Everything was run on a 2018 Intel MacBook Pro without an NVIDIA GPU, so most training ran on the CPU.
- `pytorch_2_intro` is not complete: the `torch.compile()` experiments need an NVIDIA GPU. The reason is explained at the end of the notebook.

## Tools

Python, PyTorch, torchvision, matplotlib, pandas, scikit-learn, torchmetrics, mlxtend, torchinfo
