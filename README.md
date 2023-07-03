# gpt-edge
This is a repo that makes Large Language Models available for everyone who would like to experiment with this new emergent technology. The project is possible thanks to GGML and Enigma Virtual Box. If you have used realesrgan-vulkan binaries you will love this project!

### Available binaries

- [x] [gpt-2](https://github.com/appvoid/gpt-edge/releases/download/gpt-2/gpt-2.exe)
- [ ] gpt-j
- [ ] llama

### Basic parameters
```
# taking gpt-2 binary as example
-m | [optional] this is the name of the ggml model from the current model's family you would like to use, for example, gpt-2-124m.bin
-t | number of total cpus you want to use, never use more than you have or will get slow
--temp | this is the "creativity" of the model, a value near zero means repetition, a value near to one means off-topic.
-h | this will show a help message
```

### Keep in mind that...
It's important to note that I'm releasing the base models, which are not finetuned nor aligned in any way. So use with caution for user-facing apps.
