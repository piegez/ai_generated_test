# Comparação de Imagens Geradas por IA e Imagens Reais

Este projeto investiga a capacidade de distinguir entre imagens geradas por inteligência artificial (IA) e imagens reais de mulheres com diversas etnias e características físicas. Uma rede neural foi desenvolvida e treinada para realizar esta tarefa, utilizando um conjunto limitado de 100 imagens.

## 📌 Objetivo

Explorar os desafios e limitações de diferenciar imagens geradas por IA de imagens reais, analisando o desempenho de uma rede neural simples treinada para essa finalidade.

## 🚀 Tecnologias Utilizadas

- **Python**: Linguagem principal.
- **Google Colab**: Ambiente de desenvolvimento para treinar e testar o modelo.
- **Bibliotecas**:
  - TensorFlow/Keras: Para criação e treinamento da rede neural.
  - Matplotlib: Para visualização de resultados.
  - NumPy: Para manipulação de dados.

## 🖼️ Dados

- **Tamanho do conjunto**: 200 imagens.
  - 100 imagens reais de mulheres com diversidade étnica e física.
  - 100 imagens geradas por IA.
- **Formato**: As imagens foram pré-processadas para serem compatíveis com o modelo.

## 🔍 Metodologia

1. **Pré-processamento dos Dados**:
   - As imagens foram redimensionadas e normalizadas para o intervalo [0, 1].
2. **Arquitetura do Modelo**:
   - Uma rede neural simples foi implementada com camadas convolucionais e densas.
3. **Treinamento e Teste**:
   - Dados divididos em 70% para treino, 15% para validação e 15% para teste.
   - Treinamento realizado em 10 épocas.

## 📊 Resultados

- **Loss no Teste**: 0.6696  
- **Acurácia no Teste**: 66.67%

### Análise dos Resultados

Os resultados indicam que a tarefa de distinguir entre imagens geradas por IA e imagens reais é desafiadora. A acurácia de 66.67% sugere que, com o conjunto limitado de dados utilizado, o modelo apresenta desempenho próximo ao acaso (50%), mas ainda é capaz de aprender padrões básicos.

### Limitações

- **Tamanho do conjunto de dados**: Apenas 100 imagens foram utilizadas, o que limita a capacidade de generalização do modelo.
- **Arquitetura simples**: O modelo pode ser melhorado com arquiteturas mais avançadas e/ou pré-treinadas.

## 🌟 Próximos Passos

- Ampliar o conjunto de dados para incluir mais imagens geradas por IA e reais.
- Experimentar redes neurais mais complexas, como ResNet ou EfficientNet.
- Realizar análises qualitativas para identificar quais características das imagens são mais desafiadoras para o modelo.
