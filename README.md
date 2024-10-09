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

```
nome_da_app/
    ├── __init__.py        # Indica que este diretório é um pacote Python
    ├── admin.py           # Configurações para o painel de administração
    ├── apps.py            # Configurações da app
    ├── migrations/        # Diretório para migrações de base de dados
    │   └── __init__.py
    ├── models.py          # Modelos da app (estrutura dos dados)
    ├── tests.py           # Testes para a app
    └── views.py           # Lógica de visualização da app
```

---

## Definições

### URLs

URLs são responsáveis por mapear endereços web a funções ou vistas no backend. Basicamente, quando um utilizador acede a uma página, o URL indica ao Django qual código deve ser executado para gerar a resposta certa.

### Views

As Views em Django são funções ou classes que processam pedidos (requests) dos utilizadores e devolvem respostas. Elas atuam como intermediárias entre os dados (do modelo) e o que o utilizador vê (templates). Basicamente, uma view recebe o pedido, processa os dados e devolve uma página web ou outro tipo de resposta, como JSON ou ficheiros.

### Organização de URLs e Views

Ao desenvolver aplicações com Django, a organização das URLs e Views desempenha um papel fundamental na forma como os pedidos dos utilizadores são tratados. Quando um utilizador acede a uma página da aplicação, o URL correspondente define qual o código que deve ser executado no backend.

Cada app pode ter o seu próprio ficheiro urls.py. Facilita a leitura e a gestão do código à medida que a aplicação cresce.