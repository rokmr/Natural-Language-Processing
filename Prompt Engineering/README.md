# Prompt Engineering 

Prompt engineering is the process of creating a prompting function fprompt(x) that results in the most effective
performance on the downstream task.

## Two main varieties of prompts: 
1. *Cloze Prompts* (Petroni et al., 2019; Cui et al., 2021), which fill in the blanks of a textual string, and ->tasks that are solved using masked LMs,
2. *Prefix prompts* (Li and Liang, 2021; Lester et al., 2021), which continue a string prefix. -> tasks regarding generation, or tasks being solved using a standard auto-regressive LM

Prompt type is being choosen on the basis of the task and the model.

### Manual Template Engineering :

Manually create intuitive templates based on human introspection

### Automatic Template Learning :

Automate the template design process. 

This can further separated into **discrete prompts**, where the prompt is an actual text string, and **continuous prompts**, where the prompt is instead described directly in the embedding space of the underlying LM.

One other orthogonal design consideration is whether the prompting function fprompt(x) is **static**, using essentially the same prompt template for each input, or **dynamic**, generating a custom template for each input. 


# Resources:

## Courses 

1. [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)

## Papers:
* [A Systematic Survey of Prompting Methods in Natural Language Processing ](https://arxiv.org/pdf/2107.13586.pdf)


