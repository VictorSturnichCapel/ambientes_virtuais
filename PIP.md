Essa biblioteca possui como função gerenciar as dependências do Python.

Comandos:

pip list -> listar dependências

pip install -> instala dependências

pip freeze -> mostra todas as dependências

pip freeze | grep -v "^-e" | xargs pip uninstall -y -> remover todos os pacotes