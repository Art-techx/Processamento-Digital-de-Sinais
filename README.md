# Digital Signal Processing using Python (Baseado no Livro Digital Signal Processing using MATLAB)

## Visão Geral

Este repositório contém resumos e implementações em Python dos principais conceitos abordados no livro *Digital Signal Processing using MATLAB*, adaptados para Google Colab. O objetivo é explorar cada tópico por meio de análise computacional.

Cada capítulo inclui:

- **Resumo teórico detalhado** 📖
- **Explicação das equações principais** 📊
- **Conversão de códigos MATLAB para Python** 🔄
- **Links para vídeos explicativos** 🎥

## Estrutura do Repositório

Cada capítulo listado abaixo possui um link correspondente para um notebook no Google Colab contendo todos os itens mencionados.

## Conteúdos

### **Capítulo 4: A Transformada-z**

📌 [Notebook/Colab](https://colab.research.google.com/drive/1iTAHm1wj9RlVbknMIXgbDbclwKG-pIVf) | 🎥 [Vídeos](https://youtu.be/a4ilqPa6l34?si=oIaKKL-rix-SMsC-)

- Definição da transformada-z bilateral e unilateral.
- Determinação da região de convergência (ROC) e suas implicações na estabilidade do sistema.
- Propriedades fundamentais da transformada-z.
- Cálculo da inversa da transformada-z.
- Representação de sistemas no domínio-z.
- Solução de equações de diferenças usando a transformada-z.

### **Capítulo 5: Transformada Discreta de Fourier (DFT)**

📌 [Notebook/Colab](https://colab.research.google.com/drive/1pqpXBGngvTrUIPifbly_0us5butGywbV) | 🎥 [Vídeos](https://youtu.be/71WWCtYd7Lo?si=3b9IQyYeWO-qB4Um)

- Introdução à Série de Fourier Discreta.
- Amostragem e reconstrução no domínio-z.
- Definição e propriedades da DFT.
- Uso da DFT para convolução linear.
- Implementação e otimização com a Transformada Rápida de Fourier (FFT).

### **Capítulo 6: Implementação de Filtros Discretos no Tempo**

📌 [Notebook/Colab](https://colab.research.google.com/drive/1YSYgBzgvCsSIP8gbxIAe7Oj6A9baZBbl) | 🎥 [Vídeos](https://youtu.be/MgyrrXGTsok?si=isnk3nL4hGkfX19D)

- Estruturas básicas de filtros digitais.
- Implementação de filtros IIR e FIR.
- Estruturas lattice para filtros digitais.
- Efeitos de quantização e precisão finita.
- Representação numérica e análise dos erros introduzidos.

### **Capítulo 7: Projeto de Filtros FIR**

📌 [Notebook/Colab](https://colab.research.google.com/drive/1b8iSZjhVxR8MQHhqKe7QFCAXdrefbMay) | 🎥 [Vídeos](https://www.youtube.com/live/u_tFWolPZY0?si=95fwgcqHr_CyGCLt)

- Propriedades dos filtros FIR de fase linear.
- Métodos de projeto baseados em janelas.
- Técnicas de amostragem em frequência.
- Design ótimo utilizando a técnica de equirripple.

### **Capítulo 8: Projeto de Filtros IIR**

📌 [Notebook/Colab](https://colab.research.google.com/drive/13CBFwjdCyv_2qmtmFXrzJuKKw7X_O0e3) | 🎥 [Vídeos](https://youtu.be/jLnhm4JgmCw?si=LP6tufeKl7ilqOhG)

- Características dos filtros analógicos protótipos.
- Transformações de filtros analógicos para digitais.
- Projeto de filtros digitais Butterworth e Chebyshev.
- Transformações de banda para diferentes aplicações.

### **Capítulo 12: Aplicações em Comunicações**

📌 [Notebook/Colab](https://colab.research.google.com/drive/1_gqRvQDD9MHGrrjj21xjwfCZQB8UC2Nc) | 🎥 Vídeos

- Modulação por Código de Pulso (PCM). [🎥](#)
- PCM diferencial (DPCM) e PCM adaptativo (ADPCM). [🎥](#)
- Modulação Delta (DM) e Modulação Delta Adaptativa (ADM). [🎥](#)
- Codificação preditiva linear (LPC) aplicada à voz. [🎥](#)
- Geração e detecção de sinais DTMF (Dual-tone Multifrequency). [🎥](#)
- Aplicações de detecção de sinal em comunicações digitais e espectro expandido.

## Como Usar

1. Acesse os notebooks no Google Colab através dos links fornecidos.
2. Execute as células de código para visualizar os resultados.
3. Assista aos vídeos explicativos para aprofundamento.
