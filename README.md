# 🖼️ Lazy Loading de Imagens com JavaScript

Projeto simples desenvolvido para praticar o **efeito de lazy loading em imagens**, utilizando a **Intersection Observer API** em JavaScript puro.

A ideia é carregar imagens em **baixa resolução inicialmente** e substituir pela versão em **alta resolução apenas quando entram na viewport**, melhorando desempenho e tempo de carregamento.

---

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido para praticar:

- Conceito de **lazy loading**
- Uso da **Intersection Observer API**
- Manipulação dinâmica de atributos (`src`)
- Otimização de carregamento de imagens
- Melhoria de performance em páginas longas
- Organização básica de HTML, CSS e JavaScript
- Observação de elementos na viewport

---

## 🧰 Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**
  - Intersection Observer API

---

## ⚙️ Como funciona o lazy loading

- As imagens são carregadas inicialmente em **baixa resolução** (`w=10`)
- Um `IntersectionObserver` monitora quando a imagem entra na tela
- Ao se tornar visível:
  - A URL da imagem é atualizada para uma versão em **alta resolução** (`w=1000`)
  - A imagem deixa de ser observada
- Isso evita carregar imagens desnecessárias fora da viewport

---

## ⚙️ Funcionalidades

- Lazy loading manual via JavaScript
- Carregamento progressivo de imagens
- Otimização de performance
- Observação automática de múltiplas imagens
- Layout vertical simulando páginas longas
- Uso de imagens externas (Unsplash)

---

## Deploy do Projeto 

- https://fillipesnts.github.io/project-with-lazy-loading/
