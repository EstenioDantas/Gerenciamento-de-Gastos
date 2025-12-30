# 💰 Controle de Gastos (Expense Tracker)

> Uma aplicação web para gerenciamento financeiro pessoal, desenvolvida com foco em lógica matemática e manipulação de dados no Front-end.

## 🖼️ Sobre o Projeto

Este projeto é um **Controle de Despesas** onde o usuário pode registrar seus gastos diários. O diferencial desta aplicação é a capacidade de realizar cálculos em tempo real (atualizando o valor total automaticamente) e persistir essas informações no navegador.

O objetivo foi aprofundar os conhecimentos em **JavaScript Moderno (ES6+)**, lidando com Arrays de Objetos, métodos matemáticos e estilização CSS avançada (Flexbox e Animações).

## ✨ Funcionalidades

* **Adicionar Despesas:** Cadastro de nome e valor do gasto.
* **Cálculo Automático:** O sistema soma todos os itens da lista e atualiza o "Total" instantaneamente.
* **Validação de Dados:** Impede o cadastro de valores vazios ou inválidos (R$ 0,00).
* **Remoção de Itens:** Botão para excluir despesas, recalculando o total automaticamente para baixo.
* **Persistência (LocalStorage):** Os dados não são perdidos ao atualizar a página ou fechar o navegador.
* **Interface Responsiva:** Design moderno com tema escuro ("Dark Mode"), transições suaves e layout adaptável.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica.
* **CSS3:**
    * **Flexbox:** Para alinhamento de layout.
    * **Transitions & Keyframes:** Para animações de entrada dos itens e hover nos botões.
    * **Dark Mode:** Paleta de cores moderna e confortável.
* **JavaScript (Vanilla):**
    * Manipulação do DOM.
    * `localStorage` e `JSON`.
    * Métodos de Array: `push`, `forEach`, `filter` e `reduce` (para o cálculo de soma).

## 🧠 Aprendizados e Desafios

Durante o desenvolvimento, os principais desafios superados foram:

1.  **Lógica Matemática:** Criação da função `atualizarTotal()` que percorre o array de objetos somando os preços e atualizando a interface.
2.  **Tratamento de Tipos:** Conversão correta de Strings (do input) para Numbers (para cálculo), evitando erros de concatenação ou valores `NaN`.
3.  **Event Delegation:** Implementação da funcionalidade de excluir itens ouvindo eventos na lista pai, permitindo manipular elementos criados dinamicamente.

## 🚀 Como rodar o projeto

1.  Faça o download dos arquivos.
2.  Abra o arquivo `index.html` no seu navegador.
3.  Pronto! Adicione suas despesas e teste a persistência de dados.

---

Desenvolvido para fins de estudo por Estênio Gomes Dantas
