# Exercícios complementares: IA Generativa para Negócios

Dois exercícios de 30 minutos do MBA FGV em Inteligência Artificial e Analytics Aplicadas a Negócios. Cada um roda sozinho no Google Colab.

| Exercício | O que você faz | Abrir |
|---|---|---|
| **Classificação e NER** | Compara TF-IDF e BERTimbau, reconhece entidades e mascara dados pessoais | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/exercicios-complementares-fgv/blob/main/ner/ner.ipynb) |
| **Visão computacional e imagem** | Usa Vision Transformer e Deep Dream e treina um gerador de imagens a partir de texto | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/exercicios-complementares-fgv/blob/main/visao_computacional/visao_computacional.ipynb) |

## Como rodar

1. Clique em **Open in Colab** e entre com sua conta Google.
2. **Arquivo → Salvar uma cópia no Drive**.
3. **Ambiente de execução → Alterar o tipo de ambiente de execução → GPU T4 → Salvar**.
4. Rode as células de cima para baixo com **Shift + Enter**.

Não é preciso ter conta no Hugging Face nem chave de API.

## Estrutura

- `ner/ner.ipynb`: classificação de texto, NER e mascaramento
- `ner/dados/conversas_rotuladas.jsonl`: 60 mensagens fictícias do Banco Aurora, rotuladas à mão
- `visao_computacional/visao_computacional.ipynb`: Vision Transformer, Deep Dream e miniprojeto de imagem

## Fontes e licenças

- Reviews: [B2W-Reviews01](https://huggingface.co/datasets/ruanchaves/b2w-reviews01) (CC BY 4.0), baixado durante a execução.
- Classificação: [BERTimbau](https://huggingface.co/neuralmind/bert-base-portuguese-cased) (MIT).
- NER: [bert-base-multilingual-cased-ner-hrl](https://huggingface.co/Davlan/bert-base-multilingual-cased-ner-hrl) (AFL 3.0).
- Vision Transformer: [google/vit-base-patch16-224](https://huggingface.co/google/vit-base-patch16-224) (Apache 2.0).
- Deep Dream: Inception v3 do `torchvision`.
- Geração de imagem: [Stable Diffusion v1-5](https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5) (CreativeML OpenRAIL-M). Leia a licença antes de qualquer uso comercial.
- Fotos do mascote: [diffusers/dog-example](https://huggingface.co/datasets/diffusers/dog-example), baixadas durante a execução.

O Banco Aurora, suas regras e as mensagens são fictícios.
