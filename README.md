# Consulta Portal da Transparência

Este projeto consulta informações sobre despesas no Portal da Transparência e envia atualizações por e-mail.

## Funcionalidades

- Consulta despesas por fase (Empenho, Liquidação, Pagamento).
- Envia e-mails com os resultados encontrados para uma data específica.
- Utiliza a API do Portal da Transparência.

## Tecnologias Utilizadas

- Python
- Requests
- PyWin32
- dotenv (para gerenciamento de variáveis de ambiente)

## Pré-requisitos

Antes de executar o projeto, você precisará ter:

- Python 3.x instalado
- Dependências do projeto (listadas no `requirements.txt`)
- Uma chave da API do Portal da Transparência

## Obtendo a Chave da API

Para acessar a API, você precisa solicitar sua chave API através do site do Portal da Transparência:

1. Acesse [Portal da Transparência API](https://api.portaldatransparencia.gov.br/swagger-ui/index.html).
2. Siga as instruções para obter sua chave.

## Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/pedrovcgomes/consulta-portaltransparencia.git
   cd consulta-portaltransparencia


2. **Instale as dependências:**
   pip install -r requirements.txt
   
3. **Configure as variáveis de ambiente:**

Crie um arquivo .env na raiz do projeto com o seguinte conteúdo:

API_KEY=sua_chave_api

EMAIL_TO=seu_email

CNPJ=seu_cnpj


## Estrutura do Projeto

meu_projeto/
│
├── api.py           # Funções para consulta à API do Portal da Transparência

├── email.py         # Funções para envio de e-mails

├── main.py          # Ponto de entrada do projeto

├── requirements.txt  # Dependências do projeto

└── .env             # Variáveis de ambiente 


## Contribuição
Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, fique à vontade para abrir uma issue ou enviar um pull request.
