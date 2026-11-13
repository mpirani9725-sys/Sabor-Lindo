# 🍽️ Portal Restaurante

Sistema de gerenciamento desenvolvido para facilitar a administração de restaurantes.

## 🚀 Funcionalidades

- 📊 Dashboard
- 📦 Controle de estoque
- 👨‍🍳 Cadastro de funcionários
- ⏰ Controle de ponto
- 🏢 Recursos Humanos
- 🪑 Controle de mesas
- 🧾 Gerenciamento de pedidos
- ♻️ Controle de alimentos reciclados

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- LocalStorage

## 💻 Como executar

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto.
3. Execute o arquivo `index.html` no navegador.

## 💾 Armazenamento

O sistema utiliza LocalStorage para armazenar os dados no navegador.

## 👨‍💻 Projeto

Portal Restaurante – Sistema de Gerenciamento.

Desenvolvido para fins de estudo e gerenciamento.

<!DOCTYPE html>
0002 <html lang="pt-BR">
0003 <head>
0004 <meta charset="UTF-8">
0005 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Portal Restaurante</title>
 </head>
 <body>
 <div class="container">
 <!-- MENU PRINCIPAL -->
 <aside class="menu">
 <h2> Restaurante</h2>
 <button onclick="mostrarTela('dashboard')">Dashboard</button>
   <button onclick="mostrarTela('estoque')">Estoque</button>
   <button onclick="mostrarTela('funcionarios')">Funcionários</button>
   <button onclick="mostrarTela('controle')">Controle de Ponto</button>
   <button onclick="mostrarTela('rh')">RH</button>
   <button onclick="mostrarTela('mesas')">Mesas</button>
   <button onclick="mostrarTela('pedidos')">Pedidos</button>
   <button onclick="mostrarTela('reciclados')">Alimentos Reciclados</button>
   <button onclick="mostrarTela('relatorios')">Relatórios</button>
 </aside>
 
