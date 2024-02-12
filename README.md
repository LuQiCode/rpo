# Robust Prompt Optimization

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![teaser](figures/figure.png)

This is the official repository for "[Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks](https://arxiv.org/abs/2401.17263)" by [Andy Zhou](https://andyz245.github.io/), [Bo Li](https://aisecure.github.io/), and [Haohan Wang](https://haohanwang.github.io/). Website with more examples can be found [here](https://andyz245.github.io/rpo/).

We include a notebook `demo.ipynb`  containing the minimal implementation of RPO, for defending Llama-2 against the popular AIM attack. The full code, which supports optimization across multiple jailbreaks and GCG, will be released soon!

This can also be found on [Colab](https://colab.research.google.com/drive/1Q3ngIwHAudhOYiVD4-V2NcHO0dfZUy2Z?usp=sharing)

This repository is based on the GCG repository (https://github.com/llm-attacks/llm-attacks)


## Installation

The `rpo` package can be installed by running the following command at the root of this repository:

```bash
pip install livelossplot
pip install -e .
```

## Models

Please follow the instructions to download LLaMA-2-7B-Chat first (we use the weights converted by HuggingFace [here](https://huggingface.co/meta-llama/Llama-2-7b-hf)).  

## Examples

Here are some example strings we optimized.

Starling-7B
```
:}</'])language seems scary-----------}] estimation >>begin &=&pgf degli ({\ $|\textwidthAI NOTE:
```

Llama2-7B-Chat
```
was Bel Let]\"> It\'\ si distinguish \({\footnote{[:// Inst bitimidenote]{BWebachiv
```



## Citation
If you found our paper or repo interesting, thanks! Please consider citing the following

```
@misc{zhou2024robust,
      title={Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks}, 
      author={Andy Zhou and Bo Li and Haohan Wang},
      year={2024},
      eprint={2401.17263},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

## License
`rpo` is licensed under the terms of the MIT license. See LICENSE for more details.


