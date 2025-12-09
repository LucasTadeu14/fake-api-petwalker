# Fake API

Este repositório contém uma API fake construída com **Node.js** e **Express**, simulando um backend para um e-commerce de produtos para animais de estimação. A API inclui endpoints para obter informações sobre produtos e adicionar/remover itens de um carrinho de compras.

## Banco de Dados

A Fake API utiliza um banco de dados simulado no formato JSON com informações sobre produtos para animais de estimação. Aqui está a estrutura:

```json
{
  "products": [
    { 
      "id": 1, 
      "title": "Coleira com GPS Inteligente", 
      "description": "Monitore em tempo real a localização do seu pet com esta coleira inteligente equipada com GPS e bateria de longa duração.",
      "price": 199.00,
      "cover": "https://i.imgur.com/vquo597.png"
    },
    { 
      "id": 2, 
      "title": "Coleira com Câmera HD", 
      "description": "Veja o mundo pelos olhos do seu animal! Coleira com câmera HD embutida e transmissão via Wi-Fi direto no seu celular.",
      "price": 299.99,
      "cover": "https://i.imgur.com/5Yy1vGK.png"
    },
    { 
      "id": 3, 
      "title": "Coleira Confortável Tradicional", 
      "description": "Coleira ajustável, feita com material leve e resistente, ideal para o conforto e segurança do seu pet no dia a dia.",
      "price": 50.00,
      "cover": "https://i.imgur.com/NceMrrB.png"
    },
    { 
      "id": 4, 
      "title": "Comedouro Automático Inteligente", 
      "description": "Programe os horários das refeições do seu pet com este comedouro automático com controle via aplicativo e sensor de nível de ração.",
      "price": 100.00,
      "cover": "https://i.imgur.com/86FpoTu.png"
    },
    { 
      "id": 5, 
      "title": "Seguro para Animais de Estimação", 
      "description": "Garanta a proteção e o bem-estar do seu pet com um seguro que cobre emergências veterinárias e consultas regulares.",
      "price": 100.00,
      "cover": "https://i.imgur.com/SfeZSFF.png"
    }
  ]
}
```
## Tecnologias:

Node.js (JavaScript runtime)

Express (Framework para Node.js)

Fake API (Simulação de dados com JSON)
