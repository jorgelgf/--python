# Manual básico

## criar um ambiente virtual

python -m venv venv

[python] [criar] [criando ambient] [nome do ambiente]
---
Cuidado ao instalar pacotes, tens que criar primeiro um ambiente virtual para após instalar com pip install

Tem um arquivo chamado requirements.txt que possuí os pacotes para instalar e suas dependências
---
## para setar o prompt no ambiente virtual tem que entrar dentro da pastar bin e usar o comando:
source activate

## para desativar:
deactivate

## atualizar o pip
python -m pip install pip --upgrade

## instalar pacote de dependências
pip install -r requirements.txt

## para atualizar os pacotes necessários tens que usar o comando
pip freeze > requirements.txt

## desinstalar pacote
pip unistall mysql
