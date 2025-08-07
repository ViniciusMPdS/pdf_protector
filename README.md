## Projeto: pdf\_protector

Este projeto é uma aplicação web desenvolvida em Python com o intuito de proteger arquivos PDF.

## Tecnologias

  * Python
  * CSS
  * HTML

## Estrutura de Arquivos

  * `static`: Contém o arquivo CSS do projeto.
  * `templates`: Contém o arquivo HTML da aplicação.
  * `app.py`: Arquivo principal da aplicação, responsável pela lógica do servidor web.
  * `pdf_modifier.py`: Contém a lógica central para a modificação de arquivos PDF.
  * `requirements.txt`: Lista as dependências do projeto para que possam ser instaladas.

## Como Executar o Projeto

Para executar o projeto, siga os passos abaixo:

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/ViniciusMPdS/pdf_protector.git
    cd pdf_protector
    ```

2.  **Crie e ative um ambiente virtual (recomendado):**

    ```bash
    # Cria o ambiente virtual
    python -m venv venv
    # Ativa o ambiente virtual no Windows
    venv\Scripts\activate
    # Ativa o ambiente virtual no macOS/Linux
    source venv/bin/activate
    ```

3.  **Instale as dependências:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute o servidor:**
    O comando de execução pode variar. Tente uma das seguintes opções:

    ```bash
    # Opção 1: Comando comum para aplicações Flask
    flask run

    # Opção 2: Comando direto
    python app.py
    ```

5.  **Acesse a aplicação:**
    Abra seu navegador e acesse `http://127.0.0.1:5000` (ou o endereço que for exibido no terminal).
