# trilha-java-basico
# Desafio Controle de Fluxo

Este projeto implementa um sistema de contagem que recebe dois números inteiros via terminal e realiza a impressão incremental baseada na diferença entre eles.

## Funcionalidades

- Recebe dois números inteiros via terminal
- Calcula a quantidade de iterações (diferença entre o segundo e primeiro número)
- Imprime números incrementais no console
- Trata exceção quando o primeiro parâmetro é maior que o segundo

## Arquivos do Projeto

- `Contador.java`: Classe principal com a lógica de contagem
- `ParametrosInvalidosException.java`: Exceção personalizada para parâmetros inválidos
- `App.java`: Classe original do template

## Como Compilar

```bash
javac -d bin src/*.java
```

## Como Executar

```bash
java -cp bin Contador
```

## Exemplo de Uso

1. **Caso válido** (12 e 30):
   - Entrada: 12, 30
   - Saída: Imprime números de 1 a 18

2. **Caso inválido** (30 e 12):
   - Entrada: 30, 12
   - Saída: "O segundo parâmetro deve ser maior que o primeiro"

## Regras de Negócio

- O segundo parâmetro deve ser maior que o primeiro
- A contagem é feita pela diferença: `parametroDois - parametroUm`
- Números são impressos de 1 até a quantidade de iterações calculada

## Getting Started (Original)

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

