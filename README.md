# Django Netflix Clone 🎬

Bem-vindo ao Django Netflix Clone! Este projeto é um clone simples da Netflix, desenvolvido com Django. Ele apresenta autenticação de usuário, listagem de filmes por gênero, função de busca e uma lista personalizada de filmes para cada usuário. Vamos mergulhar!

![Screenshot do Netflix Clone](static/assets/screenshot.png)

## Índice

- [Funcionalidades](#funcionalidades)
- [Começando](#começando)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

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

- Python 3.x
- Django 4.x

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







