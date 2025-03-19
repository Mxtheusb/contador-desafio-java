# Desafio Controle de Fluxo em Java

## Descrição
Projeto de aprendizado em Java, desenvolvido como parte de um bootcamp, que implementa um contador de números incrementais com validação de parâmetros e tratamento de exceções personalizadas. Este projeto explora o controle de fluxo, manipulação de entrada de dados via terminal e a criação de exceções personalizadas em Java.

---

## Funcionalidades
- Receber dois números inteiros como entrada via terminal.
- Validar se o segundo número é maior que o primeiro.
- Lançar uma exceção customizada (`ParametrosInvalidosException`) caso a validação falhe.
- Realizar um loop `for` baseado na diferença entre os números e imprimir os valores no console.

---

## Estrutura do Projeto
O projeto contém:
1. **Classe `Contador`**:
   - Método principal (`main`) para executar a lógica do programa.
   - Captura as entradas do usuário e trata exceções.
   
2. **Classe `ParametrosInvalidosException`**:
   - Exceção personalizada para garantir que o segundo parâmetro seja maior que o primeiro.
   - Mensagem de erro: `"O segundo parâmetro deve ser maior que o primeiro"`.

---

## Exemplo de Funcionamento
### Entrada:
- Primeiro número: `12`
- Segundo número: `30`

### Saída: 
    Imprimindo o número 13 
    Imprimindo o número 14 
    Imprimindo o número 15 
    ... 
    Imprimindo o número 30


### Caso inválido:
- Primeiro número: `20`
- Segundo número: `10`

### Saída:
    O segundo parâmetro deve ser maior que o primeiro


---

## Tecnologias Utilizadas
- Linguagem: Java
- Ambiente de Desenvolvimento: Qualquer IDE Java ou linha de comando
- Recursos usados: Controle de fluxo, exceções customizadas, entrada via `Scanner`.

---

## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

2. Abra o projeto na sua IDE ou Terminal.

3. Compile o programa:
    ```Bash
    javac Contador.java

4. Execute o Programa:
    ```bash
    java Contador

5. Siga as instruções no terminal para inserir os parâmetros.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para aprimorar o projeto

