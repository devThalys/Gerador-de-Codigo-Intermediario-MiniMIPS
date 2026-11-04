# Tradutor Dirigido por Sintaxe e Gerador de Código Intermediário (MiniMIPS)

Implementação de um tradutor simplificado baseado em compiladores, capaz de ler códigos escritos em **C**, processar suas etapas estruturais e convertê-los em código **Assembly do MiniMIPS de 8 bits**.

Trabalho desenvolvido na disciplina de **Projeto Integrador III** (2º semestre de 2024) do curso de **Engenharia de Computação da Universidade Federal do Pampa (UNIPAMPA), Campus Bagé**.

## ⚙️ Como o Sistema Funciona

O fluxo do tradutor simula as etapas iniciais de um compilador por meio de quatro fases principais:

1. **Análise Léxica:** Lê o código-fonte em C, identifica os componentes fundamentais e os transforma em uma lista de *tokens*, gerando também a tabela de símbolos.
2. **Análise Sintática:** Organiza os *tokens* gerados em uma estrutura hierárquica (árvore sintática) para validar a gramática do código.
3. **Geração de Código Intermediário:** Converte a árvore sintática em uma sequência de instruções intermediárias padronizadas e independentes de arquitetura.
4. **Tradução para Assembly:** Mapeia e converte as instruções intermediárias para a linguagem Assembly do MiniMIPS de 8 bits.

## 🛠️ Tecnologias Utilizadas

- **Python**
- **PLY (Python Lex-Yacc)** — Biblioteca utilizada para a construção do analisador léxico e sintático

## 📂 Estrutura do Repositório

```text
.
├── Analisador Projeto III.ipynb                 # Notebook principal com a implementação
├── relatorio-analisador.pdf                     # Relatório LaTeX do trabalho
