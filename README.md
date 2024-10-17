
# Projeto Chatbot VONIX com Rasa

## Pré-requisitos

- Python 3.8

## Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/AleDiias/cb-rasa.git
   ```
   acesse o diretório

2. **Crie e ative um ambiente virtual:**

   ```bash
   python3.8 -m venv env
   source env/bin/activate
   ```

3. **Instale as dependências do rasa:**

   ```bash
   pip install rasa
   ```

## Comandos para rodar o Rasa

- Para iniciar o Rasa na linha de comando:

  ```bash
  rasa shell
  ```

- Para treinar o modelo:

  ```bash
  rasa train
  ```

## Observação
- Para funcionar o chatbot no rasa shell, precisa ser feito o rasa train antes!!

- Para rodar as ações personalizadas:

  ```bash
  rasa run actions
  ```
