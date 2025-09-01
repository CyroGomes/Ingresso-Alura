# e-Ticket 🎫

Um sistema simples de compra de ingressos online para diferentes tipos de assentos, desenvolvido com **HTML**, **CSS** e **JavaScript**.

O projeto permite que o usuário selecione o tipo de ingresso (Pista, Cadeira Superior ou Cadeira Inferior), informe a quantidade desejada e realize a compra, atualizando a quantidade disponível em tempo real.

---

## 💡 Funcionalidades

* Seleção do tipo de ingresso:

  * Pista
  * Cadeira Superior
  * Cadeira Inferior
* Controle de quantidade disponível de ingressos para cada tipo.
* Validação da quantidade solicitada (não permite comprar mais do que o disponível).
* Feedback ao usuário via alertas:

  * Compra realizada com sucesso.
  * Quantidade indisponível.

---

## 🖥️ Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript

---

## ⚙️ Como usar

1. Abra o arquivo `index.html` no navegador.
2. Selecione o tipo de ingresso desejado no dropdown.
3. Informe a quantidade que deseja comprar.
4. Clique no botão **Comprar**.
5. A quantidade disponível será atualizada automaticamente.


## 🔧 Observações

* A quantidade máxima de compra por vez é 10 ingressos.
* O sistema é apenas **frontend**, sem persistência de dados em banco; ao atualizar a página, os valores retornam ao original.
* Código JavaScript modularizado com funções específicas para cada tipo de ingresso (`comprarPista`, `comprarSuperior`, `comprarInferior`).

# Ingresso-Alura
