# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Enumere quais cenários de testes foram selecionados para teste. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.
 
## Feature: REGISTRAR NOME

### Passo-a-passo
- Iniciar interação
- Informar o nome 

### Resultado esperado
- Validar se o bot responde com o nome informado



## Feature: REGISTRAR GASTO

### Passo-a-passo
- Iniciar interação
- Informar o nome
- Escolher opção Registrar Gasto
- Digitar o Valor do Gasto   
- Digitar com que Gastou (Ex: Salgado / Comida)
- Digitar a sua Categoria (Ex: Alimentação)

### Resultado esperado
- Validar se o bot responde com o nome informado
- Validar se o bot responde com gasto informado
- Validar se o bot responde com o que foi utilizado o gasto informado
- Validar se o bot responde com a categoria



## Feature: CONSULTA LISTA DE GASTOS

### Passo-a-passo
- Rigistrar 3 gastos de categorias diferentes
- Escolher a opção Consulta de Gastos


### Resultado esperado
- Validar se o bot responde com os gastos registrados



## Feature: CONSULTA LISTA DE GASTOS

### Passo-a-passo
- Rigistrar 3 gastos de categorias diferentes
- Registrar registrar mais 5 gastos de mesma categoria
- Escolher a opção Consulta de Gastos


### Resultado esperado
- Validar se o bot responde com os gastos registrados
- Validar se o bot faz a somatoria dos gastos por categoria
