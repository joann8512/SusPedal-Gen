# SusPedal-Gen

This is the official repository of **Learning to Generate Piano Music With Sustain Pedals**

* [Demo Page](https://joann8512.github.io/SusPedal-Gen/)

## Dataset
The dataset used in this project, *AIlabs.tw Pop1K7*, can be found [here](https://drive.google.com/file/d/1qw_tVUntblIg4lW16vbpjLXVndkVtgDe/view?usp=sharing).

## Environment

1. Install PyTorch and fast transformer:
    - torch==1.7.0 (Please install it according to your [CUDA version](https://pytorch.org/get-started/previous-versions/#linux-and-windows-4).)
    - fast transformer :

        ```
        pip install --user pytorch-fast-transformers 
        ```
        or refer to the original [repository](https://github.com/idiap/fast-transformers)

2. Other requirements:

    ```
    pip install -r requirements.txt
    ```

## Usage
```
Pre-trained models are not included in this repository
```
### Data Preparation
- To be completed...

### Train/Inference
- Change the MODE to `train` or `inference` on lines 36 & 37


## Cite This Paper
{% raw %}
```
@article{
		 {SusPedal},
		 author = {Ching, Joann and Yi-Hsuan, Yang},
		 title = {Learning to Generate Piano Music With Sustain Pedals},
		 booktitle = {arXiv preprint arXiv:2111.01216},
		 year = {2021}
		  }
```
{% endraw %}
