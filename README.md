# 🚀 ORION Control AI

## Sistema Inteligente de Monitoramento e Diagnóstico para Missões Espaciais

### Integrantes

* Arthur Maziviero Faria — RM: 573928
* Tommaso C. Nagliatti — RM: 572147

---

## 📖 Sobre o Projeto

O ORION Control AI é uma solução desenvolvida em Python para simular o monitoramento de uma missão espacial experimental.

O sistema analisa parâmetros operacionais da missão, identifica situações de risco, gera alertas automáticos e utiliza Inteligência Artificial através da API da OpenAI para produzir diagnósticos e recomendações de ação.

O objetivo é auxiliar operadores de missão na tomada de decisão rápida diante de condições normais, de atenção ou críticas.

---

## 🎯 Funcionalidades

* Monitoramento de temperatura dos módulos
* Monitoramento do nível de energia
* Monitoramento da qualidade da comunicação
* Monitoramento do nível de oxigênio
* Monitoramento da estabilidade operacional
* Geração automática de alertas
* Classificação de risco da missão
* Tomada de decisão baseada em regras lógicas
* Integração com Inteligência Artificial (OpenAI)
* Geração automática de diagnósticos e recomendações

---

## 🧠 Inteligência Artificial

O sistema utiliza um modelo de linguagem da OpenAI para analisar os dados operacionais simulados da missão espacial.

A IA recebe informações sobre os parâmetros monitorados, identifica riscos operacionais e produz:

* Diagnóstico da missão
* Principais riscos identificados
* Recomendações de ação
* Decisão final da operação

Todo o contexto da análise é baseado em um prompt especializado para controle de missões espaciais.

---

## 🛠 Tecnologias Utilizadas

* Python
* Google Colab
* OpenAI API
* GitHub

---

## 📸 Demonstração

### Cenário Normal

![Cenário Normal](assets/Resultado%20IA%201.png)

### Cenário Crítico

![Cenário Crítico](assets/Resultado%20IA%203.png)

---

## ▶ Como Executar

1. Abra o notebook ORION_Control_AI.ipynb no Google Colab.
2. Configure sua chave da OpenAI utilizando os Secrets do Colab:

   * Nome do segredo: OPENAI_API_KEY
3. Execute todas as células em ordem.
4. Escolha um dos cenários disponíveis:

   * Operação Normal
   * Missão em Atenção
   * Missão Crítica
5. O sistema realizará a análise automática e consultará a Inteligência Artificial para gerar recomendações.

---

## 📂 Estrutura do Projeto

```text
orion-control-ai/
│
├── ORION_Control_AI.ipynb
├── README.md
│
└── assets/
    ├── Resultado IA 1.png
    └── Resultado IA 3.png
```

---

## 🎥 Vídeo de Demonstração

Link do vídeo:

(Adicionar após a gravação)

---

## ✅ Objetivo Acadêmico

Projeto desenvolvido para a disciplina Prompt and Artificial Intelligence da FIAP – Global Solution 2026.1.

A solução aplica conceitos de programação, inteligência artificial, monitoramento operacional e tomada de decisão em um cenário inspirado na indústria espacial moderna.
