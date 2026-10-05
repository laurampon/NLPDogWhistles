# NLPDogWhistles
  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge"/>  ![Made withPython](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)

  Repositório para o trabalho da disciplina de "Processamento de Linguagem Natural e de Imagens" (26/2).

## Introdução

*Dog whistles* (apitos de cachorro) são um tipo de linguagem codificada amplamente utilizada em plataformas digitais por grupos ideológicos extremistas para disseminação discreta de ódio. Esses termos são facilmente confundíveis com palavras de uso comum, tornando-os altamente suscetíveis ao contexto. Isso demonstra-se um desafio para a maioria dos modelos de processamento de linguagem natural, também conhecidos como Large Language Models (LLM). Nesse trabalho, como uma proposta da disciplina de Processamento de Linguagem Natural e de Imagens, do quarto semestre do Bacharel em Ciência e Tecnologia da Ilum (CNPEM), exploramos como modelos podem ser usados para a detecção desses termos, tanto sua presença quanto a atribuição do sentido que eles carregam dado seu contexto. 

## Metodologia

O trabalho utilizou um *Corpus* constituído por anotações provenientes dos datasets do [DogWhistle Dataset](https://huggingface.co/datasets/AstroAure/dogwhistle_dataset), construído a partir de uma coleção de datasets denominada SilentSignals, produzida pelo grupo de pesquisa SALT (*Social and Language Technologies*) da Universidade de Stanford, e do dataset [*The Pushshift Reddit Dataset*](https://arxiv.org/abs/2001.08435), que contém comentários e postagens realizados na rede social Reddit. A base de dados final contém 43.350 publicações, organizadas em três categorias: uso convencional de termos associados a *dog whistles*, uso codificado dessas expressões e ausência de termos relacionados. O objetivo foi explorar técnicas clássicas de PLN, como tokenização e embeddings, utilizando os modelos TF-IDF, Word2Vec (W2V) e um transformer, realizando o treino e teste com cada um para a etapa de classificação.

## Sobre o repositório

O arquivo `ProjetoDogWhistles.ipynb` contêm todas as etapas de pré-processamento, tokenização, embeddings, instanciação e validação dos modelos. 

As seguintes bibliotecas Python são utilizadas:

- NumPy
- Pandas
- spaCy
- NLTK
- Hugging Face Datasets
- PyTorch
- Matplotlib
- scikit-learn
- Gensim
- Transformers
- OpenAI

As demais bibliotecas utilizadas (`re`, `collections`, `json`, `os`, `getpass` e `time`) fazem parte da biblioteca padrão do Python e não precisam ser instaladas separadamente.

<h2 align="center">Contribuidores</h2>

<p align="center">
  <a href="https://github.com/laurampon">
    <img src="https://github.com/laurampon.png" width="100px" alt="Laura Medeiros Dal Ponte"/>
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/marip864">
    <img src="https://github.com/marip864.png" width="100px" alt="Mariana Melo Pereira"/>
  </a>
</p>

<p align="center">
  <sub><b>Laura Medeiros Dal Ponte</b></sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub><b>Mariana Melo Pereira</b></sub>
</p>

<h2 align="center">Professor responsável</h2>

<p align="center">
  <a href="https://github.com/jamesmalmeida">
    <img src="https://github.com/jamesmalmeida.png" width="100px" alt="Laura Medeiros Dal Ponte"/>
  </a>

  <p align="center">
  <sub><b>James Moraes Almeida</b></sub>





