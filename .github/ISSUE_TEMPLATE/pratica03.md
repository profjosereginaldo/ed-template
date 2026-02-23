---
name: "Prática 03"
about: "Template para criar a issue da pratica03"
title: "[Prática 03] – Tipos de Dados Abstratos (TDA)"
labels: ["pratica03"]
assignees: ''
---

## 🎯 Objetivo
Nesta prática, você irá:
- Criar tipos de dados abstrados em C;
- Separar a interface (.h) da implementação (.c);
- Utilizar e testar um TDA sem acessar diretamente seus dados internos.

## 📝 Instruções da Atividade
**1️⃣ Preparação do ambiente**
1. Abra o **Visual Studio Code** na pasta do seu repositório.
2. Abra um terminal e certifique-se de que está na branch `develop`.
```bash
git checkout develop
```
3. Crie e alterne para a branch desta prática.
```bash
git checkout -b feature/pratica03
```

**2️⃣ Implementação do código**
1. No painel esquerdo do VSCode, localize a pasta `praticas`.
2. Crie uma nova pasta chamada `pratica03`.
3. Desenvolva os arquivos solicitados:
- `conta.h`: Definir o tipo `Conta` e declarar os protótipos das funções `conta_criar`, `conta_depositar`, `conta_sacar`, `conta_ver_saldo` e `conta_destruir`;
- `conta.c`: Definir a struct interna `conta_t`, contendo os atributos `numero` e `saldo`, e implementar todas as funções do TDA;
- `main.c`: Testar as operações do TDA criando uma conta, realizando depósitos, saques e consultando o saldo.

**3️⃣ Compilação e execução**
1. No terminal, acesse a pasta da `pratica03`.
```bash
cd praticas/pratica03
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
git commit -m "feat: conclui pratica03. Fecha #ID"
```
3. Envie suas alterações para o GitHub.
```bash
git push origin feature/pratica03
```
4. No GitHub, clique no botão **Compare & pull request**.
5. **Importante**: Certifique-se de que o **base repository** é o seu repositório e a **base branch** é a `develop`.
6. Na descrição, escreva: `Nesta prática, implementei tipos de dados abstratos em C. Fecha #ID`.
7. Clique em **Create pull request** e envie o link do PR na plataforma de ensino para o professor.

## 📂 Estrutura Final
Seu repositório deve ficar assim:
```text
praticas/
└── pratica03/
    ├── conta.c
    ├── conta.h
    └── main.c
```