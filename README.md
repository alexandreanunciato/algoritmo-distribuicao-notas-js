# Sistema de Saque em Caixa Eletrônico (JavaScript)

## 📌 Descrição
Projeto simples em JavaScript que simula a lógica de um sistema de saque em caixa eletrônico, realizando a distribuição de notas disponíveis (50, 20 e 10) de acordo com o valor solicitado pelo usuário.

O objetivo é aplicar conceitos básicos de lógica de programação, como estruturas de repetição, validações e controle de fluxo.

## 📌 Exemplos de uso

Entrada | Saída
--- | ---
80 | 50:1 20:1 10:1
90 | 50:1 20:2 10:0
15 | Insira uma quantia valida

## ⚙️ Regras de Negócio
- O valor do saque deve estar entre 10 e 1000
- O valor deve ser múltiplo de 10
- As notas disponíveis são: 50, 20 e 10
- Caso o valor seja inválido, o sistema retorna uma mensagem de erro

## 🧠 Lógica Utilizada
A distribuição das notas é feita de forma sequencial:
1. Primeiro são retiradas as notas de 50
2. Em seguida, as notas de 20
3. Por fim, as notas de 10

## 🧪 Exemplos
| Entrada | Saída |
|-------|------|
| 80 | 50:1 20:1 10:1 |
| 90 | 50:1 20:2 10:0 |
| 15 | Insira uma quantia valida |

## 🚀 Tecnologias
- JavaScript

## 📂 Como executar
O código pode ser executado em ambientes que suportem JavaScript, como Node.js ou plataformas de desafios online.

---

Projeto desenvolvido para prática de lógica de programação.
