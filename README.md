# UpTickets

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Flet](https://img.shields.io/badge/Flet-6B5BDB?style=flat-square) ![JSON](https://img.shields.io/badge/JSON-45556C?style=flat-square)

Projeto de estudo e colaboração; este repositório é um fork de [victorprogramer121/UpTickets](https://github.com/victorprogramer121/UpTickets).

O UpTickets é um sistema de gestão voltado para a criação e administração de eventos e usuários.

## Funcionalidades

* **Gestão de Eventos:** Adição, visualização e remoção de eventos no sistema.
* **Gestão de Usuários:** Cadastro, validação de login e exclusão de contas.
* **Interface Gráfica Responsiva:** Aplicação desktop/web desenvolvida com o framework Flet.
* **Armazenamento de Dados:** Persistência de dados utilizando arquivos locais (JSON), dispensando a configuração inicial de SGBDs externos.

## Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Interface Gráfica:** Flet
* **Padrões de Projeto:** Arquitetura baseada em camadas (Models, Views, Controllers, DAOs).

## Arquitetura do Projeto

A aplicação está estruturada em módulos para facilitar a manutenção e evolução do código:

* `app.py`: Ponto de entrada da aplicação.
* `src/model/`: Contém as entidades de domínio e a camada de acesso a dados (DAO).
* `src/view/`: Telas e componentes da interface gráfica.
* `src/controllers/`: Controladores responsáveis pelas regras de negócio e integração entre view e model.
* `src/infrastructure/`: Serviços de infraestrutura e repositório de dados locais (`/database/*.json`).
* `src/main/`: Configuração e injeção de dependências para inicialização do sistema.

## Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python 3 instalado no ambiente.

1. Clone o repositório:
   ```bash
   git clone https://github.com/Kleber720/UpTickets.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd UpTickets
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install flet
   ```
4. Inicie a aplicação:
   ```bash
   python app.py
   ```


---

[← Portfólio de Kleber Amaro](https://github.com/Kleber720) · [Todos os repositórios](https://github.com/Kleber720?tab=repositories)
