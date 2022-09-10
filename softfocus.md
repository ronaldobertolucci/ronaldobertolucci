# Desafio Softfocus - Desenvolvedor Web Jr.
Este projeto foi desenvolvido como parte do processo de seleção da empresa Softfocus. Ele consiste em uma versão simplificada da comunicação de perda do sistema 
Proagro Fácil (criado pela Softfocus). 
O programa fornece uma maneira de cadastrar perdas ocasionadas por fenômenos naturais para facilitar o gerenciamento do Proagro, programa que exonera o produtor 
de obrigações financeiras em casos de perdas nas lavouras.

## Projeto construído com
Python e JavaScript:
- Django
- Bootstrap
- jQuery

## Repositório 
- O repositório público do projeto pode ser encontrado neste [link](https://github.com/ronaldobertolucci/desafio_softfocus)
- Nele estão contidas as orientações de uso e de instalação do app

## Site
- Deployment: Heroku
- Endereço [aqui](https://pagrofacil.herokuapp.com/)

## Critérios essenciais do desafio 
1. A solução deveria ser desenvolvida em Python.
2. A interface deveria ser criada em HTML.
3. A solução deveria possibilitar o CRUD de uma comunicação de perda.
4. Os dados deveriam ser salvos em um banco de dados: Postgres, MySQL, MongoDB ou Firebase.
5. A comunicação de perda deveria possuir:
    - Nome do produtor
    - email do produtor
    - CPF do produtor
    - Localização da lavoura (latitude e longitude)
    - Tipo da lavoura
    - Data da colheita
    - Evento ocorrido
6. Quando o analista estivesse cadastrando uma nova comunicação, ele deveria ser informado caso existisse no banco de dados outra comunicação em um raio de
menos de 10km com evento divergente.
7. O projeto deveria conter validações para CPF e email feitas em JavaScript.
8. Deveria ser possível realizar a busca de comunicações por CPF do produtor.
9. O projeto deveria ser disponibilizado em repositório público.
10. O projeto deveria possuir um README explicando como utilizar o app.

:white_check_mark: Todos os critérios acima foram cumpridos



