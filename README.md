# Assistente Virtual com NLP e Automação

Este projeto consiste em uma assistente virtual desenvolvida como parte de um Bootcamp de Machine Learning. A assistente utiliza processamento de linguagem natural (NLP) e automação para interpretar comandos de voz e executar ações, como abrir URLs no navegador.

## **Funcionalidades**
- **Reconhecimento de Fala:** Usa a biblioteca `SpeechRecognition` para converter áudio em texto.
- **Processamento de Comandos:** Interpreta comandos de texto utilizando regras básicas e pode ser expandida com modelos mais avançados de NLP.
- **Texto para Fala (TTS):** Responde ao usuário com áudio usando a biblioteca `pyttsx3`.
- **Automação de Ações:** Executa ações com base nos comandos, como abrir o YouTube ou Google no navegador.

## **Tecnologias Utilizadas**
- Python 3.10
- Bibliotecas: 
  - `SpeechRecognition` (Reconhecimento de fala)
  - `pyttsx3` (Texto para áudio)
  - `webbrowser` (Automação de URLs)
  - Alternativa ao `pyaudio`: `sounddevice` (para ambientes como Google Colab)

## **Como Funciona**
1. O usuário fala um comando como "Abrir YouTube".
2. A assistente converte o áudio em texto e interpreta o comando.
3. A ação correspondente é executada e uma resposta em áudio é gerada.
