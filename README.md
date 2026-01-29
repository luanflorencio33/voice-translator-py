# 🎙️ Tradutor de Voz com IA (Whisper)

> **Nota:** Este projeto foi desenvolvido para rodar exclusivamente no **Google Colab**, pois utiliza scripts específicos do ambiente para capturar áudio através do navegador.

Este projeto foi desenvolvido como parte de um desafio prático de Python na **Digital Innovation One (DIO)**. O objetivo foi criar um tradutor automatizado que utiliza o modelo **Whisper da OpenAI** para transcrever e traduzir áudio em tempo real.

## 📋 Funcionalidades

- **Gravação de Áudio na Nuvem**: Captura a voz diretamente pelo navegador usando JavaScript injetado no Colab.
- **Processamento com IA (Whisper)**: Utiliza o modelo de rede neural da OpenAI para transcrever o áudio em português e traduzi-lo para inglês com alta precisão.
- **Síntese de Voz (Text-to-Speech)**: Converte a tradução resultante em áudio usando a biblioteca gTTS.

## 🛠️ Tecnologias Utilizadas

- **Google Colab**: Ambiente de desenvolvimento.
- **[OpenAI Whisper](https://github.com/openai/whisper)**: Reconhecimento de fala (ASR) e tradução.
- **gTTS**: Conversão de texto para fala.
- **JavaScript**: Utilizado internamente nas células do notebook para gerenciar a gravação de áudio no browser.

## 🚀 Como Executar

Para testar o projeto, você não precisa instalar nada em seu computador.

1. Clique no botão **"Open in Colab"** no topo deste arquivo (ou abra o arquivo `.ipynb` manualmente no Colab).
2. No menu superior, vá em **Ambiente de Execução** > **Alterar tipo de ambiente de execução**.
3. Em "Acelerador de hardware", selecione **T4 GPU** (o Whisper funciona muito melhor com placa de vídeo).
4. Execute as células sequencialmente (clique no botão "Play" ou use `Shift + Enter`).
5. Quando solicitado na célula de gravação, **permita o acesso ao microfone** no seu navegador.

## 📚 Aprendizados

A implementação deste projeto permitiu explorar:
- A integração entre Python e JavaScript para contornar limitações de hardware na nuvem.
- O uso de modelos Transformers (Whisper) para tarefas complexas de NLP.
- Manipulação de arquivos de áudio em ambiente virtual.

---

## ✒️ Autor

Desenvolvido por **Luan Florencio** durante a formação no bootcamp Bradesco - GenAI & Dados na DIO.
Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/luanflorencio).
