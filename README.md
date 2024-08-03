# Django Netflix Clone 🎬

Bem-vindo ao Django Netflix Clone! Este projeto é um clone simples da Netflix, desenvolvido com Django. Ele apresenta autenticação de usuário, listagem de filmes por gênero, função de busca e uma lista personalizada de filmes para cada usuário. Vamos mergulhar!

![Screenshot do Netflix Clone](static/assets/screenshot.png)

## Índice

- [Status do Projeto](#status-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Começando](#começando)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Status do Projeto

🚧 **Em andamento**: Este projeto está em desenvolvimento ativo. Novas funcionalidades e melhorias estão sendo adicionadas regularmente. 


## Funcionalidades

- 🏠 **Página Inicial**: Exibe um filme em destaque e uma lista de filmes populares.
- 🔍 **Busca**: Encontre filmes pelo título.
- 🎬 **Detalhes do Filme**: Veja informações detalhadas sobre cada filme.
- 📜 **Gêneros**: Navegue por filmes por gênero.
- 📋 **Minha Lista**: Salve seus filmes favoritos em uma lista personalizada.
- 🔐 **Autenticação de Usuário**: Funcionalidade de cadastro, login e logout.

## Começando

Siga estas etapas para obter uma cópia local do projeto em execução:

### Pré-requisitos

- Python 3.12.2
- Django 4.1.7

### Instalação

1. Clone o repositório:

   ```sh
   git clone https://github.com/Elberscorrea/django-netflix-clone.git
   cd django-netflix-clone
   
2. Crie e ative um ambiente virtual:

   ```sh
   python -m venv .venv
   source .venv/bin/activate   # No Windows, use `.venv\Scripts\activate`

3. Instale as dependências:

   ```sh
   pip install -r requirements.txt

4. Aplique as migrações:

   ```sh
   python manage.py migrate

5. Crie um superusuário para acessar o painel de administração:

   ```sh
   python manage.py createsuperuser

6. Execute o servidor de desenvolvimento:

   ```sh
   python manage.py runserver

## Uso

### Painel de Administração

- Acesse o painel de administração do Django em http://127.0.0.1:8000/admin/ para gerenciar filmes e gêneros.

### Adicionando Filmes

1. Vá para o painel de administração.
   
2. Adicione novos filmes com seus detalhes (título, descrição, data de lançamento, gênero, duração e imagens).
   
### Buscando e Adicionando à Lista

- Use a barra de busca na página inicial para encontrar filmes.

- Clique nos filmes para ver os detalhes e adicioná-los à sua lista.

## Contribuição

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será muito apreciada.

1. Faça um fork do projeto.
   
2. Crie sua branch de feature (git checkout -b feature/FuncionalidadeIncrível).
   
3. Commit suas mudanças (git commit -m 'Adicionei uma Funcionalidade Incrível').
   
4. Push para a branch (git push origin feature/FuncionalidadeIncrível).
   
5. Abra um Pull Request.

## Licença

- Distribuído sob a licença MIT. Veja LICENSE para mais informações.

## Contato

Elber Correa - elber.scorrea@gmail.com

Link do Projeto: https://github.com/Elberscorrea/django-netflix-clone






