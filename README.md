# learn-pyproject

Experiments with modern python project tooling.

https://packaging.python.org/en/latest/guides/writing-pyproject-toml/
https://python-poetry.org/docs

```sh
# install poetry
curl -sSL https://install.python-poetry.org | python3 -
poetry completions bash >> ~/.bashrc
echo "source /etc/bash_completion" >> ~/.bashrc
poetry --version

# basic commands
poetry install # create venv and install dependencies
$(poetry env activate)
poetry add requests
poetry build
poetry publish
poetry show --tree
```
