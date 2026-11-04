# 🐾 Automação de Consumo de APIs: Projeto Pets (Cães e Gatos)

Este repositório contém a solução do **Desafio 01** do meu bootcamp de Python e Análise de Dados. O projeto é focado em práticas essenciais para o mercado de dados e desenvolvimento: consumo de APIs REST, manipulação de estruturas JSON, uso de laços de repetição e automação de salvamento de arquivos locais.

---

## 🚀 Tecnologias e Ferramentas Utilizadas
* **Linguagem:** Python
* **Biblioteca `requests`:** Para realização de requisições HTTP e consumo de APIs públicas.
* **Biblioteca `os`:** Para gerenciamento e criação de diretórios de forma automatizada.
* **Ambiente:** Jupyter Notebook / Google Colab.

---

## 📋 Sobre o Desafio
O objetivo principal foi estruturar códigos em Python para se conectar a APIs de terceiros, tratar os dados retornados no formato JSON e baixar arquivos de imagem de forma organizada e numerada.

O projeto foi dividido em duas partes principais:
1. **Dog CEO API:** Requisição de um lote de 5 imagens aleatórias de cães, extração dos links através da chave `message` e salvamento automatizado com indexação dinâmica (`enumerate`).
2. **The Cat API:** Requisição utilizando o parâmetro de limite (`limit=5`) para buscar imagens de gatos, extração direta dos links de cada dicionário (`item['url']`) e salvamento organizado.

---

## 💡 O que foi praticado
* Tratamento de erros e navegação em estruturas de dicionários e listas em JSON.
* Entendimento de parâmetros de URL (`/random/5` vs `?limit=5`).
* Uso de funções customizadas (`salvar`) para modularização e reuso de código.
* Organização de portfólio técnico no GitHub.

---
*Desenvolvido como parte da minha jornada de transição de carreira para Análise de Dados.*
