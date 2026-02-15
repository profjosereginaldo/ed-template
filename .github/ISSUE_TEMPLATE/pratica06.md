---
name: "Prática 06"
about: "Template para criar a issue da pratica06"
title: "[Prática 06] – Listas Lineares"
labels: ["pratica06"]
assignees: ''
---

## 🎯 Objetivo
Nesta prática, você irá:
- Implementar operações básicas de manipulação de listas;
- Testar o funcionamento de uma lista dinâmica para armazenamento dados.

## 📝 Instruções da Atividade
**1️⃣ Preparação do ambiente**
1. Abra o **Visual Studio Code** na pasta do seu repositório.
2. Abra um terminal e certifique-se de que está na branch `develop`.
```bash
git checkout develop
```
3. Crie e alterne para a branch desta prática.
```bash
git checkout -b feature/pratica06
```

**2️⃣ Implementação do código**
1. No painel esquerdo do VSCode, localize a pasta `praticas`.
2. Crie uma nova pasta chamada `pratica06`.
3. Desenvolva os arquivos solicitados:
- `lista_linear.h`: Definir o tipo `Lista` e declarar os protótipos das funções `lista_criar`, `lista_inserir`, `lista_remover`, `lista_buscar`, `lista_exibir`, `lista_esta_vazia` e `lista_destruir`;
- `lista_linear.c`: Definir a struct interna `lista_t` contendo os atributos `primeiro` e `ultimo`, a struct interna `no_t` contendo os atributos `anterior`, `valor` e `proximo`, e implementar todas as funções do TDA; 
- `main.c`: Testar as operações do TDA criando uma lista de valores inteiros, realizando inserção, remoção, busca e exibição de elementos.

**3️⃣ Compilação e execução**
1. No terminal, acesse a pasta da `pratica06`.
```bash
cd praticas/pratica06
```
2. Compile e execute cada programa:
```bash
gcc *.c -lm -o a.out
./a.out
```

## 📤 Entrega da Prática
1. Abra outro terminal do VSCode (isso garante que você esteja na pasta raiz).
2. Adicione os arquivos ao controle de versão e grave suas alterações.
```bash
git add .
git commit -m "feat: conclui pratica06. Fecha #ID"
```
3. Envie suas alterações para o GitHub.
```bash
git push origin feature/pratica06
```
4. No GitHub, clique no botão **Compare & pull request**.
5. **Importante**: Certifique-se de que o **base repository** é o repositório do professor e a **base branch** é a `develop`.
6. Na descrição, escreva: `Nesta prática, implementei uma lista linear em C. Fecha #ID`.
7. Clique em **Create pull request** e aguarde a correção do professor.

## 📂 Estrutura Final
Seu repositório deve ficar assim:
```text
praticas/
└── pratica06/
    ├── lista_linear.c
    ├── lista_linear.h
    └── main.c
```