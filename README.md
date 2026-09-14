# 🌱 VAL Plantios

Sistema de loja virtual desenvolvido em PHP, com foco na venda e apresentação de plantas ornamentais.

O projeto foi desenvolvido como uma aplicação web completa, reunindo catálogo de produtos, carrinho de compras, cadastro de usuários, autenticação e integração com banco de dados.

---

## 📋 Sobre o projeto

A **VAL Plantios** é uma loja virtual voltada para a comercialização de plantas e produtos relacionados à jardinagem.

O sistema possui uma interface desenvolvida para facilitar a navegação pelo catálogo, permitindo visualizar produtos, consultar preços, adicionar itens ao carrinho e realizar o processo de compra após a autenticação do usuário.

O projeto também conta com uma área específica para usuários cadastrados, utilizando sessões em PHP para controlar o acesso às funcionalidades restritas.

---

## ✨ Funcionalidades

### 🪴 Catálogo de produtos
- Exibição de produtos disponíveis na loja
- Imagens individuais para os produtos
- Nome e preço dos produtos
- Página de detalhes dos produtos
- Navegação pelo catálogo
- Sistema de pesquisa

### 🛒 Carrinho de compras
- Adição de produtos ao carrinho
- Alteração da quantidade de produtos
- Remoção de produtos
- Cálculo do subtotal
- Cálculo do frete
- Aplicação de cupom
- Cálculo do valor total
- Persistência do carrinho utilizando `localStorage`

### 👤 Sistema de usuários
- Cadastro de novos usuários
- Login através de CPF e senha
- Validação de CPF
- Validação de e-mail
- Criação de senha
- Autenticação através de sessões PHP
- Área exclusiva para usuários autenticados
- Encerramento de sessão (logout)

### 💳 Processo de compra
- Identificação do usuário autenticado
- Recuperação dos dados do usuário
- Visualização dos produtos selecionados
- Registro das informações relacionadas à compra
- Integração com banco de dados

### 📱 Interface
- Layout responsivo
- Navegação adaptada para diferentes tamanhos de tela
- Animações utilizando CSS e JavaScript
- Elementos visuais personalizados
- Imagens e ícones próprios do projeto

---

## 🛠️ Tecnologias utilizadas

### Front-end

- HTML5
- CSS3
- JavaScript
- SVG
- JSON
- LocalStorage

### Back-end

- PHP
- Sessões PHP
- MySQL
- SQL

### Outros

- Git
- GitHub
- Fonte Raleway

---

## 📁 Estrutura do projeto

```text
loja/
│
├── home/
│   ├── assets/
│   │   ├── imagens dos produtos
│   │   ├── banners
│   │   ├── logotipo
│   │   └── ícones SVG
│   │
│   ├── produtos/
│   │   ├── frete.json
│   │   ├── produtos.json
│   │   └── total_produtos.json
│   │
│   ├── script/
│   │   ├── carrinho.js
│   │   ├── desc_carrinho.js
│   │   ├── hero.js
│   │   ├── produto.js
│   │   ├── produto_desc.js
│   │   └── script.js
│   │
│   ├── styles/
│   │   ├── animation_title.css
│   │   ├── carrinho.css
│   │   ├── catalogo.css
│   │   ├── desc_section.css
│   │   ├── footer.css
│   │   ├── hero_section.css
│   │   ├── keyframess.css
│   │   ├── media.css
│   │   ├── navegation.css
│   │   ├── produto.css
│   │   └── styles.css
│   │
│   ├── index.php
│   ├── produto.php
│   └── processa_compra.php
│
├── login/
│   ├── assets/
│   ├── banco/
│   │   ├── cons.php
│   │   └── DLL.php
│   ├── script/
│   ├── styles/
│   ├── cad.php
│   ├── compra.php
│   ├── login.php
│   ├── processa_cad.php
│   ├── processa_compra.php
│   └── processa_login.php
│
├── loja_logado/
│   ├── assets/
│   ├── script/
│   ├── carrinho.php
│   ├── index.php
│   ├── produto.php
│   └── sair.php
│
└── raleway/
    └── arquivos da fonte Raleway
