# GPTlite

GPTlite is a Large Language Model designed for training on resource-limited computers (eg. laptops) without the need for powerful GPUs. It is based on the fast and efficient implementation of GPT-2/nanoGPT by Andrej Karpathy for natural language processing tasks.

## Installation

To install GPTlite, clone the repository and install the dependencies:

```bash
git clone https://github.com/ginomcfino/GPTlite.git
cd GPTlite
pip install -r req.txt
```

### Setup
Useful Commands:
```python
python train.py --batch_size=32 --compile=False # trains the model on 1 GPU

```

## Usage

Here's a basic example of how to use GPTlite:

```python
from gptlite import GPTLite

model = GPTLite()
response = model.generate("Hello, how can I help you today?")
print(response)
```

## Contributing

We welcome contributions! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
