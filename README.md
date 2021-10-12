# Pedal-CPtransformer

This is the official repository of **Learning to Generate Piano Music With Sustain Pedals**

* [Demo Page](https://joann8512.github.io/Pedal-CPtransformer)

## Dataset
The dataset used in this project, AIlabs.tw Pop1K7, can be found [here](https://drive.google.com/file/d/1qw_tVUntblIg4lW16vbpjLXVndkVtgDe/view?usp=sharing).

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