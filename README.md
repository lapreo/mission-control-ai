# Mission Control AI, ARES-7

FIAP, Global Solution 2026.1 | Prompt and Artificial Intelligence

## Integrantes

- Rafael Laprega Gontijo Magalhaes, RM: 561975
- Gustavo Torres de Oliveira,  RM: 572952

---

## Sobre o Projeto

Sistema inteligente de monitoramento de missao espacial desenvolvido em Python. Usa o modelo **Llama 3.2:1b via Ollama** para analisar dados simulados de temperatura, energia, sinal de comunicacao, pressao interna e nivel de oxigenio, gerando alertas automaticos e respostas da IA quando a missao entra em situacao critica.

---

# Demonstracao

# Cenario Normal
![Dados da missao](assets/dados_normais.png)

# Cenario Normal 2
![Dados da missao 2](assets/dados_normais2.png)

# Alerta Critico
![Alerta critico](assets/alerta_critico.png)

# Alerta Critico 2
![Alerta critico 2](assets/alerta_critico2.png)

---

# Funcionalidades

- Monitoramento de 5 parametros: temperatura, energia, sinal, pressao e oxigenio
- Alertas automaticos: quando parametros ultrapassam os limites criticos
- Logica de tomada de decisao automatizada (ex: energia < 20%, ativa modo de economia)
- Respostas automatizadas: para situacoes criticas simuladas
- 3 cenarios de execucao: normal, critico e monitoramento continuo (3 ciclos)
- Interface de chat: conversacional com o Mission Control AI (bonus)
- Integracao com IA generativa (Llama 3.2:1b via Ollama) com system prompt contextualizado para missao espacial

---

# Tecnologias Utilizadas

- Python
- [Ollama](https://ollama.com/), servidor local de modelos de linguagem
- Llama 3.2:1b, modelo de linguagem open source
- Google Colab, ambiente de execucao

---

## Como Executar

Abra o notebook diretamente no Google Colab:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lapreo/mission-control-ai/blob/main/mission_control_ai_fixed.ipynb)

---

## Video de Demonstracao

[Assistir ao video](https://youtu.be/AL-r_Kuxtd8)

# link: 

---

## Estrutura do Repositorio

```
- mission-control-ai/
- mission_control_ai_fixed.ipynb (Notebook principal)
- ssets/ (Prints do sistema funcionando)
- dados_normais.png
- dados_normais2.png
- alerta_critico.png
- alerta_critico2.png
- README.md
```
