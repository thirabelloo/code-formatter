# Code Formatter

Este projeto contém um script para padronizar o código utilizando as ferramentas Flake8, Black, Pylint e Vulture.

## Como Usar

Execute o script com uma das seguintes opções:

- `--flake8`: Executa o Flake8
- `--black`: Executa o Black
- `--pylint`: Executa o Pylint
- `--vulture`: Executa o Vulture
- `--all`: Executa todas as ferramentas

<br>

```sh
pipenv run python src/code_standardizer.py --all
