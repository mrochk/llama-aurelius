# Llama Aurelius
Fine-tuning Llama on Marcus Aurelius' writings using QLoRA.

Examples of generations:

```
PROMPT: 'The best reaction against the uncertitude of life is'
MODEL: 'to be content with the present, and to be satisfied with the things which are in our power.'
```

```
PROMPT: 'The way of life is'
MODEL: 'the way of the gods, and the way of the gods is the way of the universe.'
```

```
PROMPT: 'The best thing in life is'
MODEL: 'to be able to do what thou wilt, and to be able to do it at the right time.'
```

All the code can be found in the [notebook](nb.ipynb).

The training takes approximately 12 minutes on a P100 gpu.

The model is also available on my HuggingFace account:\
https://huggingface.co/mrochk/Llama-Aurelius

*References:*
- QLoRA: https://arxiv.org/abs/2305.14314
- Base Model: https://huggingface.co/meta-llama/Llama-3.2-3B
