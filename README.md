# Calculadora Multifuncional

**Alunos:**
* Pedro Henrique de Lira Tavares
* Gustavo Ferreira Rodrigues

---

### Objetivo
Desenvolver uma calculadora interativa no Flowgorithm para aplicar na prática os conceitos de lógica de programação, incluindo estruturas de repetição (`while`), tomadas de decisão encadeadas (`if/else`) e operações matemáticas com variáveis dos tipos Inteiro e Real.

---

### Ferramenta Utilizada
* **Flowgorithm** (Software para desenvolvimento e execução de algoritmos via fluxogramas).

---

### Lógica de Funcionamento do Programa
O algoritmo inicia fazendo a declaração de todas as variáveis no topo do fluxo. Em seguida, entra em uma estrutura de repetição principal (`while`) responsável por exibir o menu com as 11 opções no console.

1. O usuário digita o número da opção desejada.
2. O sistema lê o valor na variável `opcao` e direciona o fluxo através de desvios condicionais encadeados (`if`).
3. Dentro do bloco da operação selecionada, o programa solicita os valores de entrada necessários via teclado, realiza o cálculo aritmético correspondente e exibe o resultado formatado na tela.
4. Finalizado o cálculo, o fluxo retorna ao início do laço e apresenta novamente o menu, permitindo novos cálculos até que o usuário digite a opção 11 (Encerrar Programa).

---

### Estruturas Utilizadas
* **Variáveis:**
  * `opcao` (Tipo **Inteiro**): armazena o número escolhido no menu e controla a condição de parada do laço de repetição.
  * `num1`, `num2` e `resultado` (Tipo **Real**): armazenam as entradas numéricas do usuário e os resultados das operações, garantindo precisão em valores decimais.
* **Estrutura de Repetição (Laço While / Enquanto):**
  * Mantém o programa em execução contínua enquanto a condição `opcao != 11` for verdadeira.
* **Estruturas de Decisão (Condicionais If / Se):**
  * Encadeamento de condições para testar o valor da variável `opcao` e executar apenas o bloco de código correspondente.
* **Blocos de Entrada e Saída (Input / Output):**
  * Blocos de saída (`Escrever`) para exibição de mensagens, menus e resultados.
  * Blocos de entrada (`Ler`) para leitura e atribuição dos dados digitados pelo usuário.

---

### Descrição das Funções

1. **Somar (Opção 1):** Recebe dois valores reais (`num1` e `num2`), realiza a adição (`num1 + num2`) e exibe a soma.
2. **Subtrair (Opção 2):** Recebe dois valores reais, calcula a diferença (`num1 - num2`) e exibe o resultado.
3. **Multiplicar (Opção 3):** Lê dois valores e calcula o produto (`num1 * num2`).
4. **Dividir (Opção 4):** Lê o dividendo e o divisor, realizando a divisão (`num1 / num2`).
5. **Potencializar (Opção 5):** Recebe a base e o expoente, calculando a exponenciação (`num1 ^ num2`).
6. **Raiz Quadrada (Opção 6):** Recebe um único número e calcula sua raiz quadrada através da função nativa `sqrt(num1)`.
7. **Área do Triângulo (Opção 7):** Solicita a base e a altura do triângulo e aplica a fórmula geométrica `(num1 * num2) / 2`.
8. **Área da Circunferência (Opção 8):** Pede o raio do círculo e calcula a área utilizando a constante Pi: `3.14159 * (num1 ^ 2)`.
9. **Converter Fahrenheit (Opção 9):** Lê a temperatura em graus Celsius e faz a conversão através da fórmula `(num1 * 1.8) + 32`.
10. **Calcular IMC (Opção 10):** Solicita o peso em kg (`num1`) e a altura em metros (`num2`), calculando o índice pela fórmula `num1 / (num2 ^ 2)`.
11. **Encerrar Programa (Opção 11):** Interrompe o laço de repetição `while` e finaliza a execução do fluxograma.

---

### Instruções para Execução
1. Certifique-se de ter o software **Flowgorithm** instalado no computador.
2. Baixe o arquivo `.fprg` disponibilizado neste repositório.
3. Abra o arquivo no Flowgorithm.
4. Clique no botão **Executar** (ícone de Play verde ou tecla de atalho `F5`).
5. Na janela de console, digite o número da operação desejada no menu e insira os dados solicitados pelo programa.
