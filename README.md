## ChatGPT CLI

**This isn't an interface to [ChatGPT](https://chat.openai.com/chat)!** It's a poor man's version using the OpenAI API and prompting.

To install run

```sh
pip install rich openai
export OPENAI_API_KEY="<OPENAI API KEY>"
# if you want it in $PATH
cp chatgpt ~/.local/bin/
```

Features:

- [x] Markdown display of code
- [x] GNU Readline support for input

To-Do:

- [ ] Infinite context length
- [ ] Alignment with human values
