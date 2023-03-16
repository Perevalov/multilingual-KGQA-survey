# Multilingual Question Answering over Knowledge Graphs - A Survey

## List of the models and tools mentioned in the paper structured by the methods' taxonomy

The list will be constantly updated. If you have any suggestions, please, create an issue or a pull request.

### G1 Rules and Templates

#### M1.1 Syntax Tree Parsing

* [Stanford Parser](https://nlp.stanford.edu/software/lex-parser.shtml)
* [BLLIP Reranking Parser](https://github.com/BLLIP/bllip-parser)
* [Stanza](https://stanfordnlp.github.io/stanza/)
* [Spacy Dependency Parser](https://spacy.io/api/dependencyparser)
* [Universal Dependencies](https://universaldependencies.org/)

#### M1.2 Grammar Rules

* [Grammatical Framework](https://www.grammaticalframework.org/)
* [POTATO](https://github.com/adaamko/POTATO)
* [Yargy Parser](https://github.com/natasha/yargy)

#### M1.3 Logical Representations

No out-of-the-box tools were found. However, there are several libraries from the previous sections that can be used to build a logical representation of a sentence.

#### M1.4 Dictionaries, Indexes, Templates

* [Query templates from DeepPavlov](http://docs.deeppavlov.ai/en/master/features/models/kbqa.html#how-do-i-adding-templates-for-new-sparql-queries)

### G2 Statistical Methods

#### M2.1 Classical Machine Learning and Statistical Methods

* [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
* [TF-IDF](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)
* [HMM](https://github.com/hmmlearn/hmmlearn)


#### M2.2 Deep Learining Methods

* [Spacy Entity Linker](https://spacy.io/api/entitylinker)
* [BERT Multilingual](https://huggingface.co/bert-base-multilingual-cased)

### G3 Machine Translation

#### M3.1 End-to-End Machine Translation Methods

* [OpenNMT](http://opennmt.net/OpenNMT-py/)
* [Marian](https://marian-nmt.github.io/)
* [OPUS MT](https://github.com/Helsinki-NLP/Opus-MT)
* [LibreTranslate](https://libretranslate.com/)
* [Yandex Translate](https://translate.yandex.com/)
* [Google Translate](https://translate.google.com/)

#### M3.2 Enhanced Machine Translation Methods

* [KG-NMT](https://github.com/dice-group/KG-NMT)