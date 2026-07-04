# 🍕 E-Commerce Dinâmico: Venda de Pizzas

Uma aplicação interativa de e-commerce voltada para o segmento de pizzarias. O projeto simula a experiência completa do usuário, desde a navegação pelos produtos até a customização do pedido e gerenciamento do carrinho de compras em tempo real.

---

## 🧠 Engenharia de Software & Lógica Aplicada

Este projeto vai muito além do HTML/CSS básico. A inteligência da aplicação foi construída em **JavaScript Puro (Vanilla JS)** utilizando conceitos consolidados de desenvolvimento moderno:

* **Manipulação Avançada de DOM:** Criação de funções utilitárias personalizadas utilizando Arrow Functions (`const c = (el) => ...`) para otimizar a seleção e clonagem de nós de templates estruturais (`cloneNode`).
* **Gerenciamento de Estado Dinâmico:** Controle global do estado do carrinho de compras (`cart`), contadores de modais (`modalQt`) e mapeamento de chaves dos produtos (`modalKey`).
* **Tratamento de Dados e Coleções:**
  * Uso de `.map()` para renderização automatizada do catálogo.
  * Uso de `.findIndex()` e identificadores compostos (`id + '@' + size`) para agrupar produtos idênticos de mesmo tamanho ou criar novas entradas no carrinho.
  * Uso de `.splice()` para remoção precisa de itens.

---

## 📱 Funcionalidades da Aplicação

* **Interface Baseada em Dados (Data-Driven):** O layout da página inicial consome e renderiza os dados dinamicamente de uma API mockada (`pizzaJson`), simulando o comportamento de aplicações reais conectadas a bancos de dados.
* **Modal Interativo com Efeitos Visuais:** Animações controladas via JS através de temporizadores (`setTimeout`) que criam transições suaves de opacidade na abertura e fechamento da janela do produto.
* **Carrinho de Compras Inteligente:**
  * Atualização assíncrona reativa de valores através da função modular `updateCart()`.
  * Lógica integrada para cálculo automático de **Subtotal**, aplicação de **Desconto comercial (10%)** e valor **Total**.
* **Navegação Responsiva:** Eventos dedicados para controle de comportamento em dispositivos móveis (`menu-openner` e `menu-closer` manipulando a viewport).

---



## 🔧 Como Executar Localmente

1. Faça o download ou clone este repositório:
   ```bash
   git clone [https://github.com/anaaraujo27/Site-compra-de-pizzas.git](https://github.com/anaaraujo27/Site-compra-de-pizzas.git)
