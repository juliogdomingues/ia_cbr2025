# Curso Intensivo de IA - do básico ao avançado

Este repositório foi criado para o Curso Intensivo de Inteligência Artificial realizado no Congresso Brasileiro de Radiologia e Diagnóstico por Imagem de 2025.

## Programação

Conceitos básicos: Big Data, IA, ML
Features, Modelos e performance
Métricas e estatística
Prática: underfitting/overfitting
Pré-processamento de dados
Regressão Linear, Gradient Descent e Regressão Logística
Naive Bayes, Árvores de Decisão e Support Vector Machines

Redes Neurais Artificiais e Deep Learning
Redes Neurais Convolucionais
Prática: Redes Neurais Convolucionais
Modelos de Linguagem: Redes neurais Recorrentes e Transformers
Agentes de IA
Prática: ChatGPT e outros Large Language Models

## Palestrantes

Augusto Braga Fernandes Antunes
Igor Rother César de Oliveira
Júlio Guerra Domingues
Lucas Junqueira Carvalhido

## Como rodar no Google Colab

Este repositório foi pensado para ser executado diretamente no Google Colab, sem necessidade de configuração local.

Passo a passo:

1. Abra no Colab

- Acesse: https://colab.research.google.com
- Vá em “GitHub” e cole a URL do repositório: `https://github.com/juliogdomingues/ia_cbr2025`
- Escolha o notebook desejado dentro da pasta `praticas/` e clique em “Open in Colab”.

2. (Opcional) Monte o Google Drive
   Se quiser salvar resultados/arquivos no seu Drive, execute no início do notebook:

```python
from google.colab import drive
drive.mount('/content/drive')
```

3. Instale dependências específicas da prática
   Algumas práticas podem ter um `requirements.txt` próprio. Execute em uma célula no topo do notebook:

```python
!pip -q install -r requirements.txt  # se o arquivo estiver ao lado do notebook
# ou
!pip -q install -r praticas/<nome_da_pratica>/requirements.txt
```

4. Habilite aceleração por GPU (quando aplicável)

- Menu: Runtime > Change runtime type > Hardware accelerator: GPU > Save

5. Execute as células na ordem

- Use Runtime > Run all para executar o notebook inteiro, ou rode célula a célula conforme instruções do material.

Observações

- Se algum caminho de arquivo for relativo, certifique-se de que está correto em relação à estrutura do repositório.
- Caso o notebook use dados maiores, eles podem ser baixados automaticamente na primeira execução ou lidos do seu Google Drive se montado.
