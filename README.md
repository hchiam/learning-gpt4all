# Learning [gpt4all](https://github.com/nomic-ai/gpt4all)

Just one of the things I'm learning. https://github.com/hchiam/learning

A good place to start: https://github.com/hchiam/learning-gpt4all/tree/main/colab

## quick example

```py
# https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-bindings/python
# !pip install gpt4all
from gpt4all import GPT4All
model = GPT4All("orca-mini-3b-gguf2-q4_0.gguf") # , device='gpu') # device='amd', device='intel'
output = model.generate("The capital of France is ", max_tokens=10)
print(output)
```

## some helpful links

https://github.com/nomic-ai/gpt4all

https://github.com/nomic-ai/gpt4all/blob/main/gpt4all-bindings/python/README.md

https://docs.gpt4all.io/gpt4all_python.html#gpt4all.gpt4all.GPT4All.chat_completion

https://github.com/hchiam/learning-prompt-eng

## example applications

https://github.com/hchiam/html-template-generator/tree/main/gpt4all_test

https://github.com/hchiam/text-similarity-test/tree/main/gpt4all_test

## other things you might find interesting

https://github.com/hchiam/learning-localGPT

https://github.com/hchiam/learning-TinyLlama
