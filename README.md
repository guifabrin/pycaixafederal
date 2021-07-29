# pycaixafederal
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pycaixafederal)
[![PyPI version](https://badge.fury.io/py/pycaixafederal.svg)](https://badge.fury.io/py/pycaixafederal)
[![Coverage Status](https://coveralls.io/repos/github/andreroggeri/pycaixafederal/badge.svg?branch=master)](https://coveralls.io/github/andreroggeri/pycaixafederal?branch=master)
[![Maintainability](https://api.codeclimate.com/v1/badges/e550387e85d315a212af/maintainability)](https://codeclimate.com/github/andreroggeri/pycaixafederal/maintainability) [![Join the chat at https://gitter.im/pycaixafederal/pycaixafederal](https://badges.gitter.im/pycaixafederal/pycaixafederal.svg)](https://gitter.im/pycaixafederal/pycaixafederal?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Acesse seus extratos da Caixa Federal pelo Python

## Instalação
Disponível via pip

`pip install pycaixafederal`

## Aquisitando dados
Você ainda precisa ter o Warsaw instalado visto que este é um web crawler

```python
import pycaixafederal

print(pycaixafederal.get(usuario, senha))
```

## Contribuindo

Envie sua PR para melhorar esse projeto ! 😋