# 📉 Processamento de Sinais Biomédicos e Filtragem Digital

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marcosassis-UCL/Trabalho-02-Sinais-Biomedicos/blob/main/TrabalhoPDS_Filtros.ipynb)

Este projeto foi desenvolvido como parte da disciplina de **Processamento Digital de Sinais** da **Faculdade UCL**. O foco central é a aplicação de técnicas de filtragem digital em sinais acústicos reais para extração de padrões e redução de ruído em dados complexos.

---

## 🎯 Objetivos do Projeto
* **Processamento de Sinais Reais:** Analisar uma base de dados composta por sinais acústicos de materiais submetidos a atrito e compressão.
* **Filtragem Digital FIR:** Implementar filtros de Resposta ao Impulso Finita (Passa-Baixa) para atenuar ruídos e destacar componentes de baixa frequência.
* **Filtragem Digital IIR:** Implementar filtros de Resposta ao Impulso Infinita (Passa-Alta) para evidenciar microvibrações e transientes rápidos.
* **Análise Espectral (FFT):** Utilizar a Transformada Rápida de Fourier para validar o comportamento dos sinais antes e depois de cada processo de filtragem.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python 3**: Linguagem base para todo o processamento.
* **NumPy & Pandas**: Carregamento, extração de vetores e normalização dos dados.
* **SciPy (Signal)**: Ferramenta principal para o design e aplicação dos filtros FIR e IIR.
* **Matplotlib**: Criação de gráficos comparativos no domínio do tempo e da frequência.

## 🧠 Contextualização Técnica
A base de dados utilizada simula o desgaste de um material até sua ruptura. O sinal bruto contém:
1. **Ruídos naturais** do sistema de aquisição.
2. **Microvibrações** associadas ao atrito inicial.
3. **Picos rápidos** (microeventos) que indicam falhas iminentes.

A filtragem digital permite separar essas informações, tornando possível identificar quando o material se aproxima de um ponto crítico.

## 🚀 Como Executar
1. **Ambiente:** O projeto deve ser executado no **Google Colab**.
2. **Dados:** Selecione 10 arquivos aleatórios da pasta `test` do dataset para análise.
3. **Processamento:** O código realiza automaticamente a normalização, aplicação dos filtros e geração dos gráficos FFT.
4. **Relatório:** Além do código, este repositório contém as respostas teóricas sobre a eficácia de cada filtro no sinal processado.

---
**Desenvolvido por:** Marcos Vinicius de Assis & [Nome da Dupla]
**Professora:** Leticia Araújo Silva
**Instituição:** Faculdade UCL
**Prazo de Entrega:** 05/12/2025
