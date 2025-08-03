🔍 Explicações no código (comentários incluídos)

    pipeline("question-answering"): cria um modelo capaz de responder com base em um contexto textual.

    contexto: fornece o conhecimento do "copiloto" – você pode alterar conforme a necessidade.

    perguntar_ao_copiloto: função que simula a interação com um assistente virtual.

    print: exibe o resultado da conversa.

# Copiloto
Criar um “copiloto” simples em Python que responde a perguntas sobre um domínio específico (ex: dúvidas jurídicas, técnicas ou administrativas) usando um modelo de linguagem aberto.

# 🤖 Copiloto Simulado com Python

Este projeto simula um Copiloto utilizando Python e modelos da Hugging Face, com a funcionalidade básica de **responder perguntas com base em um contexto fornecido**.

> ⚠️ Este copiloto **não está integrado ao Microsoft Copilot Studio**. Ele é um protótipo educacional inspirado no conceito de copilotos de IA, sem necessidade de login ou conta Microsoft.

## 🚀 Funcionalidades

- Responde perguntas com base em um texto pré-definido (contexto)
- Utiliza modelos de linguagem abertos (transformers)
- Pode ser adaptado para domínios como:
  - Atendimento jurídico
  - Suporte técnico
  - Assistência empresarial

## 🛠️ Tecnologias Utilizadas

- Python 3
- Hugging Face Transformers

## 📦 Instalação

Rode no Google Colab ou localmente com:

```bash
pip install transformers

▶️ Como Usar

    Defina o contexto com informações sobre o tema desejado.

    Use a função perguntar_ao_copiloto("sua pergunta")

    O Copiloto responderá com base no que sabe do contexto.

📚 Exemplo
contexto = "A OAB é uma instituição que representa os advogados no Brasil."
perguntar_ao_copiloto("O que é a OAB?")

______________________________

## ATUALIZAÇÃO

# Copiloto com Fluxo de Conversa - Python + Transformers

Este projeto simula um Copiloto Inteligente com **fluxo de conversa**, inspirado nos conceitos do Microsoft Copilot Studio. A aplicação foi construída em Python e roda facilmente no Google Colab.

## 🧠 Funcionalidades

- Simula uma conversa com assistente virtual
- Perguntas baseadas em três categorias:
  - Jurídico
  - Tecnologia
  - Geral
- Respostas automatizadas com IA pré-treinada
- Fluxo interativo com saudação, escolha de tema e encerramento

## 📦 Tecnologias Utilizadas

- Python 3
- Transformers (Hugging Face)
- Google Colab (execução)

## 🚀 Como Usar

1. Rode o notebook no [Google Colab](https://colab.research.google.com/)
2. Execute todas as células
3. Siga as instruções na conversa

## 🔁 Exemplo de Conversa

