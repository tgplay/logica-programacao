# 🎲 Sorteador de Números Aleatórios

Este projeto é uma aplicação simples em HTML, CSS e JavaScript que permite ao usuário sortear números aleatórios dentro de um intervalo definido, sem repetições.

## ✨ Funcionalidades

- Define o intervalo mínimo e máximo (`de` e `até`)
- Informa a quantidade de números a serem sorteados
- Garante que não haja números repetidos
- Exibe o resultado na tela
- Permite reiniciar o sorteio facilmente

## 🚀 Como usar

1. Preencha os campos:
   - **De**: valor mínimo
   - **Até**: valor máximo
   - **Quantidade**: quantos números você deseja sortear
2. Clique no botão **Sortear**
3. Veja os números sorteados aparecerem na tela
4. Para realizar um novo sorteio, clique em **Reiniciar**

## 🧠 Lógica por trás

- Os números são sorteados com `Math.random()` e armazenados em um array.
- Antes de adicionar um novo número, o script verifica se ele já foi sorteado.
- A função `alterarStatusBotao()` habilita/desabilita o botão de reinício dinamicamente.
- O sorteio só é feito com valores válidos e coerentes.

## 🛠 Tecnologias usadas

- HTML5
- CSS3
- JavaScript Puro (Vanilla JS)

## 📁 Estrutura recomendada

