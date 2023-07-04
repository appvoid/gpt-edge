# gpt-edge
This is a repo that makes Large Language Models available for everyone who would like to experiment with this new emergent technology. If you have used realesrgan-vulkan binaries you will love this project! Currently supporting Windows 10. Releases are made with the following criteria:<br>
- Popularity
- Usefulness
- Size
If the model is too big, the one with least size is used, if the biggest of the family is less than 4 GB, it will be released as the default. Bigger sizes on models tends to perform pretty slow on consumer machines hence it would break the purpose of this repo.

### Available binaries

- [x] [gpt-2](https://github.com/appvoid/gpt-edge/releases/download/gpt-2/gpt-2.exe)
- [ ] gpt-j
- [ ] llama

### Usage
On your terminal, type this:
```./gpt-2.exe -p "Your prompt goes here"```

### Basic parameters
```
-p | this is the prompt that the model will receive
-t | number of total cpus you want to use, never use more than you have or will get slow
--temp | "creativity" of the model, value near zero means repetition, value near to one means off-topic
-h | this will show a help message
```

### Keep in mind that...
If the app takes too long, don't worry, it usually happens the first time, the next time will load faster. It's important to note that I'm releasing the base models, which are not finetuned nor aligned in any way. So use with caution for user-facing apps. As long as you are using Windows 10 or above I think you should be fine.
