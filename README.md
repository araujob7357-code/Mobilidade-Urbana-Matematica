# Mobilidade Urbana Inteligente — Modelagem Matemática

**Aluna:** Beatriz da Silva Araújo — RM 570619
**Desafio:** Global Solution 2026.2 - CitizenTech

## 📋 Sobre o Projeto
Este projeto aplica conceitos de Álgebra Linear (sistemas lineares, matrizes e transformações lineares) para solucionar um problema de gestão de frota de transporte público urbano. O objetivo é diagnosticar a distribuição atual de 72 ônibus entre quatro regiões (Norte, Sul, Leste e Oeste) e propor uma política de redistribuição baseada na demanda de passageiros.

## 🛠️ Tecnologias Utilizadas
- Python 3
- NumPy (Cálculos matriciais)
- Matplotlib (Visualização de dados)

## 📊 Resultados Matemáticos
1. **Etapa 1 (Diagnóstico):** O sistema linear montado a partir dos dados operacionais possui determinante igual a zero. Isso prova matematicamente que o sistema é **indeterminado** (infinitas soluções). Utilizou-se a pseudo-inversa (mínimos quadrados) para encontrar uma distribuição viável.
2. **Etapa 2 (Redistribuição):** Foi criada uma Matriz de Transformação Linear (T) para mover veículos entre as regiões. A matriz foi construída de forma que a soma de suas colunas seja 1, garantindo que a frota total de 72 ônibus seja preservada e que não haja valores negativos.

## 🚀 Como Executar
O código está disponível no arquivo `mobilidade_urbana.ipynb`.
Você pode executá-lo diretamente no Google Colab ou em qualquer ambiente Jupyter que possua as bibliotecas `numpy` e `matplotlib` instaladas.

---
*Este projeto foi desenvolvido para a disciplina de Modelagem Matemática e Computacional.*
