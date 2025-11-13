# Calculadora
Estrutura HTML
A estrutura HTML é simples e contém:

Um contêiner principal (div.calculator) que centraliza a calculadora.

Uma tela (input.calculator-screen) para exibir os números e resultados.

Um teclado (div.calculator-keys) contendo botões para números, operadores e funcionalidades adicionais.

Estilo com CSS
O CSS é utilizado para estilizar a calculadora de forma agradável:

Centralização do contêiner na tela.

Estilo para a tela de exibição e botões.

Diferenciação de botões operacionais com cores diferentes.

JavaScript
O JavaScript faz toda a funcionalidade do projeto:

Seleciona elementos do DOM para manipulação.

Gerencia o estado atual da entrada, a entrada anterior e o operador atual.

Atualiza a tela da calculadora.

Controla a lógica de cálculo, incluindo entrada de números, operadores, e funcionalidades adicionais.

Configuração Inicial:

Variáveis currentInput, previousInput, e operator para gerenciar o estado da calculadora.

Eventos de Clique:

Evento de clique nos botões para controlar a lógica de cálculo e atualizar a tela.

Funções Principais:

updateScreen(): Atualiza a tela da calculadora com o valor atual.

handleOperator(): Lida com a lógica dos operadores.

calculate(): Realiza o cálculo com base nos valores e operadores fornecidos.

clearAll(): Reseta todos os valores para o estado inicial.

inputNumber(): Lida com a entrada de números.

inputDecimal(): Lida com a entrada do ponto decimal.
