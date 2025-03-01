# embedchain

[![PyPI](https://img.shields.io/pypi/v/embedchain)](https://pypi.org/project/embedchain/)
[![Discord](https://dcbadge.vercel.app/api/server/6PzXDgEjG5?style=flat)](https://discord.gg/CUU9FPhRNt)
[![Twitter](https://img.shields.io/twitter/follow/embedchain)](https://twitter.com/embedchain)
[![Substack](https://img.shields.io/badge/Substack-%23006f5c.svg?logo=substack)](https://embedchain.substack.com/)
[![Open in Colab](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/138lMWhENGeEu7Q1-6lNbNTHGLZXBBz_B?usp=sharing)

Embedchain is a framework to easily create LLM powered bots over any dataset. If you want a javascript version, check out [embedchain-js](https://github.com/embedchain/embedchainjs)

## 🤝 Schedule a 1-on-1 Session

Book a [1-on-1 Session](https://cal.com/taranjeetio/ec) with Taranjeet, the founder, to discuss any issues, provide feedback, or explore how we can improve Embedchain for you.

## 🔧 Quick install

```bash
pip install --upgrade embedchain
```

## 🔍 Demo

Try out embedchain in your browser:

[![Open in Colab](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/138lMWhENGeEu7Q1-6lNbNTHGLZXBBz_B?usp=sharing)

## 📖 Documentation

The documentation for embedchain can be found at [docs.embedchain.ai](https://docs.embedchain.ai).

## 💻 Usage

Embedchain empowers you to create chatbot models similar to ChatGPT, using your own evolving dataset.

### Data Types Supported

* Youtube video
* PDF file
* Web page
* Sitemap
* Doc file
* Code documentation website loader
* Notion

### Queries

For example, you can use Embedchain to create an Elon Musk bot using the following code:

```python
import os
from embedchain import App

# Create a bot instance
os.environ["OPENAI_API_KEY"] = "YOUR API KEY"
elon_bot = App()

# Embed online resources
elon_bot.add("https://en.wikipedia.org/wiki/Elon_Musk")
elon_bot.add("https://tesla.com/elon-musk")
elon_bot.add("https://www.youtube.com/watch?v=MxZpaJK74Y4")

# Query the bot
elon_bot.query("How many companies does Elon Musk run?")
# Answer: Elon Musk runs four companies: Tesla, SpaceX, Neuralink, and The Boring Company
```

## 🤝 Contributing

Contributions are welcome! Please check out the issues on the repository, and feel free to open a pull request.
For more information, please see the [contributing guidelines](CONTRIBUTING.md).

For more reference, please go through [Development Guide](https://docs.embedchain.ai/contribution/dev) and [Documentation Guide](https://docs.embedchain.ai/contribution/docs).

<a href="https://github.com/embedchain/embedchain/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=embedchain/embedchain" />
</a>

## Citation

If you utilize this repository, please consider citing it with:

```
@misc{embedchain,
  author = {Taranjeet Singh},
  title = {Embedchain: Framework to easily create LLM powered bots over any dataset},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/embedchain/embedchain}},
}
```
