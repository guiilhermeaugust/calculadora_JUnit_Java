# 🧮 Calculadora com Testes Unitários (JUnit)

Este projeto é uma **calculadora simples em Java**, desenvolvida com o objetivo de demonstrar o uso de **testes unitários utilizando JUnit 5**.  
A aplicação contém operações básicas (soma, subtração, multiplicação e divisão) e uma suíte de testes automatizados para validar seu correto funcionamento.

---

## ⚙️ Funcionalidades

| Operação        | Método                | Descrição                                    |
|-----------------|----------------------|----------------------------------------------|
| ➕ Soma          | `somar(a, b)`         | Retorna a soma de dois números.              |
| ➖ Subtração     | `subtrair(a, b)`      | Retorna a diferença entre dois números.      |
| ✖️ Multiplicação | `multiplicar(a, b)`   | Retorna o produto entre dois números.        |
| ➗ Divisão       | `dividir(a, b)`       | Retorna o quociente entre dois números. Lança exceção em caso de divisão por zero. |

---

## 🧪 Testes Unitários

Os testes foram implementados usando **JUnit 5** e validam o comportamento de cada método da classe `Calculadora`.

Exemplos de validação:
- Soma de números positivos e negativos
- Subtração com diferentes sinais
- Multiplicação por zero
- Divisão por valores positivos e negativos
- Exceção ao dividir por zero (`IllegalArgumentException`)

---
