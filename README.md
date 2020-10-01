# Natural Language Processing in Julia

This repo contains the code accompanying the [JuliaCon 2020](https://juliacon.org/2020/) talk - [Natural Language Processing in Julia](https://live.juliacon.org/talk/Z8WWNV) where I present the packages the NLP research packages written during Google Summer of Code. The talk is meant for a broader audience and people without much experience in Natural Language Processing can also attend the talk.

## Abstract:
The JuliaText ecosystem provides various packages for working with human languages. In this talk, we show the usage of these JuliaText packages with Flux.jl for Natural Language Processing (NLP) with a **focus on deep learning-based approaches**.

## Description:
Natural Language Processing (NLP) enables the computers to analyse, understand and read human languages. In the past decade, tremendous growth has been witnessed in NLP owing to milestones like word embeddings, neural networks for NLP, attention and pre-trained language modelling. JuliaText packages, together with Flux, makes Deep Learning for NLP easy in Julia.

### Packages
We will start with an overview of natural language processing. Then we pick up the task of Sentiment Analysis and discuss following packages:

- WordTokenizers.jl provides various high-speed tokenizers and APIs for writing custom tokenizers for natural languages.
- CorpusLoaders.jl contains a variety of (lazy) loaders for NLP corpora.
- Embeddings.jl for working with Word Embeddings.
- Flux.jl for neural networks.
Next we move on to some other NLP pipelines and discuss some APIs from TextAnalysis.jl

Overall the attendees will gain working knowledge about how to apply the package for NLP in Julia, including the latest research developments in the field.


## Contents of this Repo
- `sentiment_weights.bson`: The pretrained weights for sentiment analysis model.
- `Sentiment.ipynb`: A jupyter notebook to load the pretrained sentiment model and play around with it.
- `WordTokenizers.ipynb`: A jupyter notebook Walkthrough for various Tokenizers in WordTokenizers.jl

## Requirements

- Julia 1.X: Download the binary from [Julialang's website](https://julialang.org/downloads)
- Julia packages
  - BSON >= 0.2.5: `pkg> add BSON@0.2.5`
  - Flux < 0.10: `pkg> add Flux@0.8.3`
  - WordTokenizers: `pkg> add WordTokenizers`
- Jupyter Notebook in Julia: Follow the guide from [IJulia's README](https://github.com/JuliaLang/IJulia.jl#quick-start)

# License

MIT

