# KLEA

## Installation

```bash
sudo apt-get install libsndfile1 python3-dev
wget https://huggingface.co/spaces/seanghay/KLEA/resolve/main/G_60000.pth
# G_60000.pth must be in the same folder where you `uv run` 
uv run --with 'klea @ https://github.com/djsamseng/KLEA' python -c 'import klea; klea.run_for_word("ទឹកធ្លាក់", "ទឹកធ្លាក់.wav")'
```
