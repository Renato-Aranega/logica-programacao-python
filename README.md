# 🐍 Lógica de Programação e Estruturas de Dados com Python (`logica-programacao-python`)

> Repositório estruturado de algoritmos, estruturas de dados elementares e implementação de projetos em Python 3 para consolidação dos fundamentos de Ciência da Computação e Engenharia de Software.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Paradigm](https://img.shields.io/badge/Paradigma-Imperativo%20%7C%20Estruturado-brightgreen.svg)](#módulos-técnicos)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📌 Visão Geral

Este repositório reúne um conjunto de exercícios progressivos e algoritmos essenciais desenvolvidos em Python. O material cobre desde os alicerces da sintaxe e raciocínio lógico até a manipulação de estruturas multidimensionais e a criação de uma aplicação prática de CRUD interativo para console.

---

## 📚 Módulos e Categorização dos Exercícios

A organização dos códigos reflete a evolução de complexidade algorítmica:

### 1. 🔀 Fundamentos de Sintaxe e Controle de Fluxo
- **Arquivo:** [`Estudo/Maior ou menor de idade.py`](./Estudo/Maior%20ou%20menor%20de%20idade.py)
- **Conceitos:** Entrada de dados (`input`), casting primitivo (`int`), avaliação booleana e estruturas condicionais compostas (`if`, `elif`, `else`).

### 2. 🔁 Estruturas de Repetição
- **Arquivo:** [`Estudo/Laços de Repetição.py`](./Estudo/Laços%20de%20Repetição.py)
- **Conceitos:** Laços determinísticos (`for` associado a `range()`) e indeterminísticos (`while`), controle de interrupção com sentinelas e tratamento de fluxo de iteração.

### 3. 📊 Vetores e Manipulação de Listas Unidimensionais
- **Arquivo:** [`Estudo/Lista [Vetor].py`](./Estudo/Lista%20[Vetor].py)
- **Conceitos:** Listas mutáveis em Python, append de elementos, indexação posicional, iteração direta e agregação de dados.

### 4. 🧮 Matrizes Bidimensionais (Estruturas Aninhadas)
- **Arquivo:** [`Estudo/Matriz.py`](./Estudo/Matriz.py)
- **Conceitos:** 
  - Matrizes 4x2 representadas por listas de listas.
  - Varredura e preenchimento por coordenadas bidimensionais (`linha x coluna`).
  - Acumuladores e somatório dos elementos.
  - Algoritmo de pertinência e busca otimizada com `any(valor in linha for linha in matrizes)`.

### 5. 🧩 Funções Modulares e Parâmetros
- **Arquivo:** [`Estudo/Funções e parâmetros.py`](./Estudo/Funções%20e%20parâmetros.py)
- **Conceitos:** Modularização, definição de escopo (`local` vs `global`), passagem de argumentos e retorno de valores tipados.

### 6. 💼 Projeto Prático: CRUD de Agenda de Contatos
- **Arquivos:** [`Estudo/Código fonte (Agenda de Contatos).py`](./Estudo/Código%20fonte%20(Agenda%20de%20Contatos).py) e [`Estudo/Projeto.AgendaDeContatos.py`](./Estudo/Projeto.AgendaDeContatos.py)
- **Conceitos e Arquitetura:**
  - Aplicação interativa para terminal (CLI) orientada a menu numérico contínuo.
  - **Create (C):** Registro de novo contato com validação de dados de telefone e formatação de string.
  - **Read (R):** Varredura completa da agenda ou busca linear O(n) por nome através de `enumerate` com saída parametrizada.
  - **Update (U):** Atualização seletiva dos campos de um contato existente após pesquisa com persistência in-memory.
  - **Delete (D):** Remoção segura de registros através da manipulação do índice indexado na lista.
  - **Validação Robusta:** Tratamento de exceções com `try/except ValueError` para garantir integridade das opções numéricas do usuário.

---

## 🚀 Como Executar

### Pré-requisitos
- **Python 3.8+** instalado.

### Execução dos scripts
```bash
# Clone o repositório
git clone https://github.com/Renato-Aranega/logica-programacao-python.git
cd logica-programacao-python

# Executar a Agenda de Contatos
python "Estudo/Código fonte (Agenda de Contatos).py"

# Executar operações com Matrizes
python "Estudo/Matriz.py"
```

---

## 👤 Autor
Desenvolvido por **[Renato Barbosa Aranega](https://github.com/Renato-Aranega)**.