# Fluxo de Conversão de Áudio em Texto e Resposta com IA

Este é um projeto da DIO: Conversando por Voz Com o ChatGPT Utilizando Whisper (OpenAI) e Python.
Que integra **Python** e **JavaScript** para permitir interação por voz com inteligência artificial.  

## 🎙️ Etapa 1: Gravação de Áudio
- Foi implementado um código que combina **Python** e **JavaScript**.
- O **JavaScript** é responsável por capturar o áudio do usuário através do navegador.
- O **Python** recebe esse áudio e prepara-o para processamento.

## 🧠 Etapa 2: Transcrição com Whisper
- O áudio gravado é enviado para o **Whisper**, uma IA especializada em **Speech-to-Text**.
- O Whisper converte a fala do usuário em texto de forma precisa e eficiente.

## 🤖 Etapa 3: Resposta com ChatGPT
- O texto transcrito é enviado para a **API do ChatGPT**.
- O ChatGPT interpreta a mensagem e gera uma resposta contextualizada em texto.

## 🔊 Etapa 4: Conversão em Áudio com gTTS
- A resposta textual do ChatGPT é convertida novamente em áudio utilizando o **Google Text-to-Speech (gTTS)**.
- O usuário recebe a resposta em formato de voz, fechando o ciclo de interação.

---

## 📌 Resumo do Processo
1. **Gravação de áudio** → (Python + JS)  
2. **Transcrição** → Whisper (áudio → texto)  
3. **Resposta** → ChatGPT (texto → resposta)  
4. **Síntese de voz** → gTTS (texto → áudio)  

Este fluxo permite que o usuário se comunique com a IA de forma natural, utilizando apenas a voz, e receba respostas também em áudio.

## 🚀 Melhorias Efetuadas 
-Durante os testes, foi notado uma falha em que o chat gpt respondia em markdown fazendo com que no audio fala-se varias vezes cerquilha, então foi implementado um código para que não fosse falado isso pelo chat
