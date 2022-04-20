# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de componentes

![Untitled Diagram drawio](https://user-images.githubusercontent.com/15042689/164129915-90d312d0-d3c5-45e7-b44e-7db0cf91b65e.png)

## Tecnologias Utilizadas

- Take Blip: usado para desenvolver o chatbot e integrar com o Telegram
- Node.js: usado para desenvolver a API de suporte para o chatbot
- MongoDB: usado para armazenar os registros de gastos e informações úteis
- Heroku: usado para hospedar a solução de API e dados
- GitHub: usado para versionamento da API


## Hospedagem

- A hospedagem do chatbot é realizada pela própria ferramenta Take Blip, sem a necessidade de configuração adicional, apenas a integração com o canal (neste caso, o Telegram)
- Para a hospedagem da API será utilizado o Heroku
- Para o banco de dados também será utilizado o Heroku
