# Literature Search

Here the commands for automatic literature search are listed. We use the following research databases:
* [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp)
* [ACM DL](https://dl.acm.org/)
* [Springer](https://link.springer.com/)
* [DBLP](https://dblp.org/)
* [ACL Anthology](https://aclanthology.org/)
* [Cyberleninka](https://cyberleninka.ru/)

And we search for publications published between 2011 and 2023 years.

## Intuition behind the queries

There a three main aspects that need to be matched in the literature and therefore reflected in the search queries:
* Data basis -- Knowledge Graphs or RDF data;
* System basis -- Question Answering systems;
* Multilingual feature.

Note: The search is case-INsensitive.

## IEEE Xplore

Note: only English data (no results in German or Russian).

1. Go to "Command Search";
1. Paste/enter the query and "Search";
1. Choose ONLY Conferences and Journals. --> "Apply";
1. Set the Year Range 2011-2023. --> "Apply".

Search anywhere.

The query:
```
("Knowledge Base*" OR "Knowledge Graph*" OR "DBpedia" OR "Wikidata" OR "YAGO" OR "Semantic Web" OR "Linked Data" OR "RDF" OR "data web" OR "SPARQL" OR "Query Graph" OR "Web data" OR "WWW" OR "web of data" OR "QALD*" OR "SimpleQuestions" OR "WebQuestions" OR "WebQSP" OR "LC-QuAD" OR "RuBQ" OR "SimpleDBpediaQA" OR "ComplexWebQuestions" OR "CWQ") AND
("Semantic search" OR "Question Answer*" OR "Question-Answer*" OR "KBQA" OR "KGQA" OR "KB QA" OR "KB-QA" OR "KG-QA" OR "KG QA" OR "NLI" OR "NLIDB" OR "QA" OR "Natural Language Interface") AND
("multilingual*" OR "multi-lingual" OR "crosslingual*" OR "cross-lingual" OR "cross linguistic" OR "internationalized" OR "multilingualism" OR "multilinguistic" OR "multilanguage" OR "bilingual" OR "many languages" OR "multiple languages" OR "several languages" OR "more than one language")
```

**Getting structured data:** open the `network` tab of the developer console in your browser. Find there `xyz` request and copy its response.

## ACM DL

Note: only English data (German supported but no relevant results).

1. Go to "Advanced Search";
1. Paste/enter the three conditions;
1. In "Publication Date", use the custom range 2011, 2023. --> "Search";

The query:
```
1st Condition (anywhere): "Knowledge Base*" OR "Knowledge Graph*" OR "DBpedia" OR "Wikidata" OR "YAGO" OR "Semantic Web" OR "Linked Data" OR "RDF" OR "data web" OR "SPARQL" OR "Query Graph" OR "Web data" OR "WWW" OR "web of data" OR "QALD*" OR "SimpleQuestions" OR "WebQuestions" OR "WebQSP" OR "LC-QuAD" OR "RuBQ" OR "SimpleDBpediaQA" OR "ComplexWebQuestions" OR "CWQ"

2nd Condition (anywhere): "Semantic search" OR "Question Answer*" OR "Question-Answer*" OR "KBQA" OR "KGQA" OR "KB QA" OR "KB-QA" OR "KG-QA" OR "KG QA" OR "NLI" OR "NLIDB" OR "QA" OR "Natural Language Interface"

3rd Condition (anywhere): "multilingual*" OR "multi-lingual" OR "crosslingual*" OR "cross-lingual" OR "cross linguistic" OR "internationalized" OR "multilingualism" OR "multilinguistic" OR "multilanguage" OR "bilingual" OR "many languages" OR "multiple languages" OR "several languages" OR "more than one language"
```

**Getting structured data:** select all search results and export `.bibtex` citations.

## Springer

Note: English and German data.

1. Select "Computer Science" discipline;
1. Enter "Date published" between 2011 and 2023;
1. Enter the query to the Search field and press search button;
1. Refine the search by selecting "Content type" either: Chapter or Article;
1. Optional: refine by language (English or German).

The English query:
```
("Knowledge Base*" OR "Knowledge Graph*" OR "DBpedia" OR "Wikidata" OR "YAGO" OR "Semantic Web" OR "Linked Data" OR "RDF" OR "data web" OR "SPARQL" OR "Query Graph" OR "Web data" OR "WWW" OR "web of data" OR "QALD*" OR "SimpleQuestions" OR "WebQuestions" OR "WebQSP" OR "LC-QuAD" OR "RuBQ" OR "SimpleDBpediaQA" OR "ComplexWebQuestions" OR "CWQ") AND
("Semantic search" OR "Question Answer*" OR "Question-Answer*" OR "KBQA" OR "KGQA" OR "KB QA" OR "KB-QA" OR "KG-QA" OR "KG QA" OR "NLI" OR "NLIDB" OR "QA" OR "Natural Language Interface") AND
("multilingual*" OR "multi-lingual" OR "crosslingual*" OR "cross-lingual" OR "cross linguistic" OR "internationalized" OR "multilingualism" OR "multilinguistic" OR "multilanguage" OR "bilingual" OR "many languages" OR "multiple languages" OR "several languages" OR "more than one language")
```

The German query:
```
("Wissensdatenbank*" OR "Wissensbasis*" OR "Wissensgraph*" OR "DBpedia" OR "Wikidata" OR "YAGO" OR "Semantic Web" OR "Linked Data" OR "RDF" OR "SPARQL" OR "Web daten" OR "WWW" OR "QALD*" OR "SimpleQuestions" OR "WebQuestions" OR "WebQSP" OR "LC-QuAD" OR "RuBQ" OR "SimpleDBpediaQA" OR "ComplexWebQuestions" OR "CWQ") AND
("semantische Suche" OR "Beantworten von Fragen" OR "Frage-Antwort-System*" OR "KBQA" OR "KGQA" OR "KB QA" OR "KB-QA" OR "KG-QA" OR "KG QA" OR "QA" OR "natürlichsprachliche Interface" OR "Question Answering") AND
("mehrsprachig*" OR "vielsprachig*" OR "Mehrsprachigkeit" OR "Vielsprachigkeit" OR "Multilingualität" OR "internationalisiert*" OR "bilingual" OR "viele Sprachen" OR "mehrere Sprachen")
```

**Getting structured data:** click `download search results (CSV)` icon.

## DBLP

Note: only English data (German supported, but no relevant results)

1. Enter the query to the Search field and press search button;
1. Refine the search by selecting years of publication between 2011 and 2023;

The query:
```
DBpedia|Wikidata|YAGO|Semantic|Linked|RDF|Web|SPARQL|Graph|WWW KBQA|KGQA|QA|NLI|Question-Answer lingual|cross|multi|linguistic
```

**Getting structured data:**  export search results as `.bibtex`

## ACL Anthology

Note: only English data. There is no native interface for search, go directly to **Getting structured data**.

**Getting structured data:**
1. Download ACL Anthology source `.bib` file from here: https://aclanthology.org/anthology+abstracts.bib.gz;
1. Load the `.bib` file into a program e.g., using Python's `bibtexparser`;
1. Implement a search query.

The query:
```
("Knowledge Base*" OR "Knowledge Graph*" OR "DBpedia" OR "Wikidata" OR "YAGO" OR "Semantic Web" OR "Linked Data" OR "RDF" OR "data web" OR "SPARQL" OR "Query Graph" OR "Web data" OR "WWW" OR "web of data" OR "QALD*" OR "SimpleQuestions" OR "WebQuestions" OR "WebQSP" OR "LC-QuAD" OR "RuBQ" OR "SimpleDBpediaQA" OR "ComplexWebQuestions" OR "CWQ") AND
("Semantic search" OR "Question Answer*" OR "Question-Answer*" OR "KBQA" OR "KGQA" OR "KB QA" OR "KB-QA" OR "KG-QA" OR "KG QA" OR "NLI" OR "NLIDB" OR "QA" OR "Natural Language Interface") AND
("multilingual*" OR "multi-lingual" OR "crosslingual*" OR "cross-lingual" OR "cross linguistic" OR "internationalized" OR "multilingualism" OR "multilinguistic" OR "multilanguage" OR "bilingual" OR "many languages" OR "multiple languages" OR "several languages" OR "more than one language")
```


## Cyberleninka

Note: only Russian data.

1. Paste the queries into the search field

The queries:
* `многоязычные вопросно ответные системы` -- English translation: multilingual question answering system
* `генерация SPARQL запросов для ответа на вопросы` -- English translation: SPARQL query generation for question answering

**Getting structured data:** Open the network tab in the browser and save the response of the `search` request.
