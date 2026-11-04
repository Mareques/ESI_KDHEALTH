# 📄 Documento de Visão — ESI-KDHEALTH

> **Disciplina:** Engenharia de Software I · Instituto Piaget
> **Projeto:** Farmácia virtual

---

## (a) 🎯 Objetivo

Desenvolver uma **farmácia virtual**: uma aplicação web que permite encomendar medicamentos e produtos de saúde online.

---

## (b) 🌍 Escopo

Lojas farmacêuticas.

---

## (c) 👥 Partes interessadas (stakeholders)

| Quem | Como beneficia |
|---|---|
| **Pessoas com mobilidade reduzida** | Podem encomendar os medicamentos de que necessitam de forma mais fácil, sem se deslocarem |
| **Pessoas idosas** | Podem encomendar os medicamentos de que necessitam de forma mais fácil |
| **Lojas farmacêuticas** | Passam a ter um canal de venda online |

---

## (d) 🧑‍💻 Equipa do projeto

| Nome | GitHub |
|---|---|
| Diogo Marques | [@Mareques](https://github.com/Mareques) |
| Kevin Rosa | [@kappa-30](https://github.com/kappa-30) |

---

## (e) ⚙️ Características do sistema

**Característica principal:** interface de fácil interpretação, que facilita a experiência do utilizador.

**Lista de funcionalidades:**

| # | Funcionalidade | Como ajuda | Estado |
|---|---|---|---|
| 1 | Registo e login simples | Poucos campos e mensagens de erro claras | Planeado |
| 2 | Catálogo por categorias (medicamentos sem receita, ajudas de mobilidade, higiene) | Encontrar o que precisam sem ter de pesquisar | Planeado |
| 3 | Pesquisa que tolera erros de escrita | Quem escreve devagar ou com dificuldade ainda encontra o produto | Planeado |
| 4 | Carrinho e compra em poucos passos | Menos ecrãs, menos hipóteses de desistir ou errar | Planeado |
| 5 | Entrega ao domicílio com morada guardada | Não precisam de sair de casa | Planeado |
| 6 | Botões para aumentar e diminuir o tamanho da letra | Ajuda quem tem problemas de visão | Planeado |
| 7 | Interface simplificada: botões grandes, texto claro, uma ação por ecrã | Ajuda quem tem dificuldade com tecnologia ou tremor nas mãos | Planeado |
| 8 | Área de administração: gerir produtos, stock e estado das encomendas | A loja precisa disto para funcionar | Planeado |

---

## (f) 🏗️ Arquitetura de referência

Esquema **provisório** (as tecnologias ainda estão por definir):

```mermaid
flowchart LR
    U["👤 Utilizador<br/>(browser)"] --> W["🌐 Aplicação Web"]
    W --> D[("🗄️ Base de Dados")]
    W -.->|opcional| L["🤖 LLM"]
```

---

## (g) ⚠️ Restrições do produto

- **Falhas técnicas a nível de código**, por ser a primeira vez que a equipa trabalha com o GitHub.

---

## (h) 🤖 Integração LLM *(opcional)*

A definir pela equipa.
