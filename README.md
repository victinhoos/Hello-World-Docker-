<div align="center">

<img src="https://github.com/user-attachments/assets/fa8ea2f5-9b77-4567-851d-2f8845a7b59f" width="100%">

</div>

# 🐳 Hello World Docker – Apache + PHP

> Um projeto simples criado para estudo do Docker, utilizando um servidor Apache com suporte a PHP para exibir um clássico **Hello World** dentro de um container.

---

## 📖 Sobre o Projeto

O **Hello World Docker** tem como objetivo introduzir o funcionamento de containers utilizando Docker, Apache e PHP.

A aplicação é propositalmente simples: um arquivo PHP que imprime "Hello World" estilizado em uma página, executado dentro de um container baseado na imagem oficial `php:8.2-apache`.

Este repositório serve como base de aprendizado para:

- Como criar um Dockerfile funcional  
- Como rodar um servidor Apache com PHP dentro de um container  
- Estruturar volumes e permissões  
- Compreender a estrutura de projetos containerizados  

---

## ✨ Funcionalidades

- **Servidor Apache rodando em container**  
  Utilizando a imagem oficial `php:8.2-apache`.

- **Execução de código PHP**  
  O container processa e renderiza o arquivo `index.php`.

- **Layout simples e customizado**  
  Página minimalista usando HTML + CSS.

- **Ideal para quem está começando com Docker**  
  Projeto direto, limpo e descomplicado.

---

## 🛠️ Tecnologias Utilizadas

### **Backend / Servidor**
- PHP 8.2  
- Apache 2  
- Docker  

### **Frontend**
- HTML5  
- CSS3  

## 🚀 Como Executar

### 1️⃣ Clone o repositório  
```bash
git clone https://github.com/victinhoos/Hello-World-Docker.git

### 2️⃣ Entre na pasta do projeto
```bash
cd Hello-World-Docker

###  3️⃣ Construa a imagem
```bash
docker build -t hello-world-docker .

### 4️⃣ Execute o container
```bash
docker run -d -p 8080:80 hello-world-docker

###5️⃣ Acesse no navegador
```bash
👉 http://localhost:8080
