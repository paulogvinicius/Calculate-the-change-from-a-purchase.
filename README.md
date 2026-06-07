# 🪙 Calculadora de Troco Simples em Java

![Java Version](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)

Um script minimalista e direto em Java projetado para calcular e exibir o troco de uma transação comercial simples. Ideal para estudos iniciais de lógica de programação e manipulação de variáveis numéricas.

---

## 💻 O Código

```java
public class CalcularTroco {
    public static void main(String[] args) {
        // Definição dos valores da transação
        double compra = 35.50;
        double pago = 50.00;

        // Cálculo do troco
        double troco = pago - compra;

        // Exibição do resultado
        System.out.println("Troco: R$ " + troco);
    }
}
