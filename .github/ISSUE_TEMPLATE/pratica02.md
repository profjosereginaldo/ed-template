---
name: "Prática 02"
about: "Template para criar a issue da pratica02"
title: "[Prática 02] – Introdução à Análise de Algoritmos"
labels: ["pratica02"]
assignees: ''
---

## 🎯 Objetivo
Nesta prática, você irá:
- Implementar soluções diferentes para o mesmo problema;
- Identificar a quantidade de operações executadas por um algoritmo;
- Analisar a complexidade assintótica de algoritmos simples;
- Calcular o tempo de execução de um algoritmo.

## 📝 Instruções da Atividade
**1️⃣ Preparação do ambiente**
1. Abra o **Visual Studio Code** na pasta do seu repositório.
2. Abra um terminal e certifique-se de que está na branch `develop`.
```bash
git checkout develop
```
3. Crie e alterne para a branch desta prática.
```bash
git checkout -b feature/pratica02
```

**2️⃣ Implementação do código**
1. No painel esquerdo do VSCode, localize a pasta `praticas`.
2. Crie uma nova pasta chamada `pratica02`.
3. Desenvolva os arquivos solicitados:
- `fatorial.c`: Ler um número inteiro positivo e calcular o seu fatorial de duas formas: utilizando repetição; e utilizando recursividade. Indicar a complexidade assintótica de cada solução.
- `busca_sequencial.c`: Ler um vetor com 100 números e procurar um valor informado pelo usuário utilizando a busca sequencial. Indicar a complexidade assintótica do algorítimo analisando o melhor caso e o pior caso.
- `exibe_matriz.c`: Percorrer uma matriz 10x10 de duas maneiras diferentes: com dois laços aninhados; com apenas um laço. Calcular o tempo de execução para cada abordagem. Indicar a complexidade assintótica das duas soluções.

**3️⃣ Compilação e execução**
1. No terminal, acesse a pasta da `pratica02`.
```bash
cd praticas/pratica02
```
2. Compile e execute cada programa:
```bash
gcc nome_do_arquivo.c -lm -o a.out
./a.out
```

## 📤 Entrega da Prática
1. Abra outro terminal do VSCode (isso garante que você esteja na pasta raiz).
2. Adicione os arquivos ao controle de versão e grave suas alterações.
```bash
git add .
git commit -m "feat: conclui pratica02. Fecha #ID"
```
3. Envie suas alterações para o GitHub.
```bash
git push origin feature/pratica02
```
4. No GitHub, clique no botão **Compare & pull request**.
5. **Importante**: Certifique-se de que o **base repository** é o repositório do professor e a **base branch** é a `develop`.
6. Na descrição, escreva: `Nesta prática, implementei algoritmos em C e analise sua complexidade assintótica. Fecha #ID`.
7. Clique em **Create pull request** e aguarde a correção do professor.

## 📂 Estrutura Final
Seu repositório deve ficar assim:
```text
praticas/
└── pratica02/
    ├── busca_sequencial.c
    ├── exibe_matriz.c
    └── fatorial.c
```