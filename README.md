# awesome-model-cards
Resources related to the model cards for machine learning (Mitchell *et al.*, 2019 – [link](https://research.google/pubs/pub48120/))

## Introduction

- What are model cards, and why do we need them?

Model cards are a list of information about the newly developed ML models, with the purpose of encouraging safe/ethical use of such systems by transparent model reporting. As many novel applications of ML continue to emerge, ML research community should do their best to minimize the negative impact of their work.

- Why do we need a list of papers that have a model card?

At the time of writing (Mar. 2021), to my best knowledge, less than 10 papers did actually make the card for their model, where the model card paper itself was cited more than 250 times. To encourage the actual adoption of the model card, I decided to make and maintain the list of papers with model cards here.

## List of papers with model card

*Note:* The list may be incomplete and your contribution to making this list better will be highly appreciated. This is in reverse chronological order. Date = initial publication of the paper.

| Name w/ card link                                            | Research Topic                    | Date       |
| ------------------------------------------------------------ | --------------------------------- | ---------- |
| [CLIP](https://github.com/openai/CLIP-featurevis/blob/master/model-card.md) | Representation learning, CV+NLP   | 2021.01.05 |
| [DALL-E](https://github.com/openai/DALL-E/blob/master/model_card.md) | Text-to-Image synthesis, CV+NLP   | 2021.01.05 |
| [BRAVE-NET](https://www.frontiersin.org/articles/10.3389/frai.2020.552258/full#supplementary-material) | Brain vessel segmentation, CV     | 2020.09.25 |
| [TOXICITY](https://github.com/conversationai/perspectiveapi/blob/master/model-cards/English/toxicity.md) | Text toxicity classification, NLP | 2020.09.24 |
| [GPT-3](https://github.com/openai/gpt-3/blob/master/model-card.md) | Language model, NLP               | 2020.05.28 |
| [PULSE](https://arxiv.org/pdf/2003.03808.pdf#page=12)        | Super resolution, CV              | 2020.03.08 |
| [CTRL](https://github.com/salesforce/ctrl/blob/master/ModelCard.pdf) | Language model, NLP               | 2019.09.10 |
| [GPT-2](https://github.com/openai/gpt-2/blob/master/model_card.md) | Language model, NLP               | 2019.02.14 |

## Further reading list

I'm not an expert on AI ethics, but I could find some useful resources for further reading as follows:

- Card-type ML paper writing guidelines
  - [Datasheets for Datasets](https://arxiv.org/abs/1803.09010)
  - [FactSheets: Increasing Trust in AI Services through Supplier's Declarations of Conformity](https://arxiv.org/abs/1808.07261)
  - [Energy Usage Reports: Environmental awareness as part of algorithmic accountability](https://arxiv.org/abs/1911.08354)
    - Though it is questionable whether those detailed measurements are practically possible, StyleGAN2-ADA reported the total amount of energy consumption for their research: [link](https://arxiv.org/pdf/2006.06676.pdf#page=37)
- [TensorFlow model card toolkit](https://github.com/tensorflow/model-card-toolkit) ([Google AI blog post](https://ai.googleblog.com/2020/07/introducing-model-card-toolkit-for.html))
- [visenger/Awesome-ML-Model-Governance @ GitHub](https://github.com/visenger/Awesome-ML-Model-Governance)
- [Increasing Transparency in Perspective's ML Models](https://medium.com/jigsaw/increasing-transparency-in-machine-learning-models-311ee08ca58a)

## Contributing

Found a missing paper in the list? Willing to have some healthy discussion? Please make an Issue or Pull Request here.

Since I'm not fully dedicated on maintaining this repository, it may take some time to respond to the Issues/PRs here. However, I'll be eventually reviewing them since one of my core values are ensuring the safe/ethical usage of such advanced technology.

## License

MIT

