 Sistema de Gerenciamento de Pedidos

Sistema web desenvolvido para uma marmitaria, com o objetivo de melhorar a organização dos pedidos e a comunicação entre o caixa e a cozinha.

O projeto foi desenvolvido como parte de um projeto acadêmico de Engenharia da Computação e foi aplicado em um ambiente real.

---

## 📸 Demonstração do sistema

### 🏠 Tela inicial

![Tela inicial](imagens/sistema.png)

### 🧾 Tela do Caixa

![Tela do Caixa](imagens/caixa.png)

### 👨‍🍳 Tela da Cozinha

![Tela da Cozinha](imagens/cozinha.png)

 Sobre o projeto

Antes do desenvolvimento do sistema, os pedidos eram comunicados entre o caixa e a cozinha de forma mais manual.

Durante as visitas e conversas com o estabelecimento, foram identificadas necessidades relacionadas à organização dos pedidos, comunicação entre os funcionários, identificação de prioridades e acompanhamento dos pedidos.

A partir dessas necessidades, foi desenvolvido um sistema web com duas interfaces principais:

-  Interface do Caixa
-  Interface da Cozinha

O objetivo é permitir que o pedido seja registrado no caixa e enviado para a cozinha em tempo real.

---

 Funcionalidades

 Caixa

- Cadastro de pedidos
- Seleção de produtos
- Controle de quantidade
- Adição de observações
- Seleção do tipo de pedido
- Balcão
- Entrega
- Entrega parceira
- Identificação automática de pedidos prioritários
- Envio do pedido para a cozinha

 Cozinha

- Recebimento dos pedidos em tempo real
- Visualização dos produtos
- Visualização das quantidades
- Visualização das observações
- Identificação de pedidos prioritários
- Alerta sonoro para novos pedidos
- Contagem do tempo do pedido
- Organização dos pedidos por prioridade
- Alteração do status do pedido para "Pronto"

---

 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Firebase
- Cloud Firestore
- Git
- GitHub

---

 Estrutura do projeto


sistema-gerenciamento-restaurante/
│
├── caixa.html
├── cozinha.html
├── index.html
├── alerta.mp3
├── firebase.json
├── .firebaserc
├── package.json
├── package-lock.json
│
└── servidor/
    ├── package.json
    └── package-lock.json
