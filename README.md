# Django Blog Tutorial

Este projeto foi criado seguindo as etapas do tutorial do Django Girls. Ele ensina como criar um blog com Django, permitindo que você aprenda os conceitos fundamentais do framework.

- 🌐 **Link do tutorial**: [Django Girls Tutorial](https://tutorial.djangogirls.org/pt/)
- 🌐 **Projeto Online na Python Anywhere**: [Acesse o site](https://otaviossousa.pythonanywhere.com/)

## 📖 Sobre o Projeto
Este é um site de blog simples criado como parte do tutorial do Django Girls. Ele inclui funcionalidades como a criação, edição e visualização de postagens, oferecendo uma excelente introdução aos fundamentos do Django.

## 📝 Anotações Notion
As anotações e tratamentos de erros que podem aparecer durante o desenvolvimento(deploy) deste projeto podem ser encontrados no Notion: [Notion](https://nettle-fontina-e72.notion.site/Django-Girls-2024-1355a694d38e8085a843d4d58efa9ae3)

## 🚀 Funcionalidades
- Adicionar e editar postagens.
- Visualizar a lista de postagens no blog.
- Interface amigável e fácil de navegar.
  
## 🛠️ Como Configurar e Executar Localmente
1. Clone o repositório:
  ```bash
  git clone <URL do repositório>
  cd nome-do-projeto
  ```
2. Crie um ambiente virtual:
  ```bash
  python3 -m venv venv
  source venv/bin/activate  # Em Windows: venv\Scripts\activate
  ```
3. Instale as dependências:
  ```bash
  pip install -r requirements.txt
  ```
4. Execute as migrações e inicie o servidor:
  ```bash
  python manage.py migrate
  python manage.py runserver
  ```
5. Acesse o projeto: Abra seu navegador e vá para http://127.0.0.1:8000/
