# DjangoWithExtraCoffee ☕️

Repositório simples para aprender Django! 

---

## Comandos

### Criar um projeto novo:

` django-admin startproject mypage `

### Iniciar o servidor de desenvolvimento:

` python3 manage.py runserver `

### Criar uma nova app dentro do projeto:

` python3 manage.py startapp challenges `

No Django, uma app é uma parte do projeto que realiza uma função específica. É uma forma de modularizar o código, permitindo que cada app trate de um aspecto particular da aplicação web. Cada app pode conter modelos (models), visualizações (views), URLs, formulários (forms) e outros componentes necessários para implementar uma funcionalidade específica.

As apps ajudam a dividir o projeto em partes menores e gerenciáveis. Uma app pode ser reutilizada em diferentes projetos. Com as apps, o código do projeto é mais organizado. Cada app tem a sua própria lógica e dados.

nome_da_app/
    ├── __init__.py        # Indica que este diretório é um pacote Python
    ├── admin.py           # Configurações para o painel de administração
    ├── apps.py            # Configurações da app
    ├── migrations/        # Diretório para migrações de base de dados
    │   └── __init__.py
    ├── models.py          # Modelos da app (estrutura dos dados)
    ├── tests.py           # Testes para a app
    └── views.py           # Lógica de visualização da app
