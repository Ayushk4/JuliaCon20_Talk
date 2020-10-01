# Natural Language Processing in Julia

This repo contains the code accompanying the [JuliaCon 2020](https://juliacon.org/2020/) talk - [Natural Language Processing in Julia](https://live.juliacon.org/talk/Z8WWNV) where I present the packages the NLP research packages I contributed during Google Summer of Code 2019 programme with the Julia Language. The talk is meant for a broader audience, so people without much experience in Natural Language Processing can also attend the talk.

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

## Queries, Suggestions and Contributions

Please abide the [Julia Community Standards and Code of Conduct](https://julialang.org/community/standards/), for all the communications and contributions.

- For Julia's NLP package or Flux for NLP related queries or suggestions, ask on [julia slack](https://slackinvite.julialang.org/) in the `#natural-language` channel or raise an issue on the specific packages. Please tag me in the query, so that I get a notification.
- For all other queries such as Julia language related questions or issues with other packages, please ask on [discourse](https://discourse.julialang.org/) or [julia slack](https://slackinvite.julialang.org/).

Please contact on public platforms mentioned above (discourse, GitHub-issues, Slack) so that others with similar queries or suggestions can also benefit. If absolutely necessary, then you may contact me by mail with your queries, but the response may be slower this way.

# License

MIT

