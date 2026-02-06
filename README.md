📌 Meu Primeiro Flask

Um projeto simples de exemplo usando o Flask, um microframework web em Python para criar aplicações web de forma rápida e leve.

🧠 Sobre

Este projeto é uma introdução ao Flask, com uma estrutura básica de aplicação que separa:

main.py – arquivo principal para iniciar o servidor

models.py – definição de modelo(s) de dados

views.py – rotas e lógica de resposta

templates/ – arquivos HTML de frontend

static/ – CSS, JS, imagens e outros recursos estáticos

Objetivo: aprender como estruturar e rodar uma aplicação Flask simples.

🚀 Tecnologias

Python

Flask (framework web)

HTML (templates Jinja2)

Arquivos estáticos (CSS/JS)

📁 Estrutura do Projeto
```plaintext
meu-primeiro-flask/
│
├── pycache/ # Arquivos compilados do Python
│ ├── main.cpython-314.pyc
│ └── views.cpython-314.pyc
│
├── static/
│ └── style.css # Estilos da aplicação
│
├── templates/
│ └── index.html # Página principal
│
├── venv/ # Ambiente virtual
│ ├── Include/
│ ├── Lib/
│ └── Scripts/
│
├── .gitignore
├── pyvenv.cfg
├── LICENSE
├── main.py # Arquivo principal
├── models.py # Modelos de dados
├── views.py # Rotas da aplicação
└── README.md
```
🔧 Pré-requisitos

Antes de rodar o projeto, instale:

Python 3.x

(Opcional) ambiente virtual

📥 Como instalar e executar

Clone o repositório

git clone https://github.com/pitombeira1984/meu-primeiro-flask.git
cd meu-primeiro-flask


Crie e ative um ambiente virtual

python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows


Instale as dependências

pip install flask


Execute a aplicação

python main.py


Abra no navegador
Vá para:
👉 http://127.0.0.1:5000

🛠️ O que você pode aprender com esse projeto

✔ Como iniciar um projeto Flask
✔ Estruturar arquivos Python para rotas, modelos e lógica
✔ Renderizar templates HTML
✔ Servir arquivos estáticos
✔ Conceitos básicos de rotas web e HTTP

📌 Licença

Este projeto está sob a licença MIT.

💬 Contribuição

Contribuições são bem-vindas!
Se quiser melhorar o projeto, crie um fork, faça as mudanças e abra um pull request 😊
