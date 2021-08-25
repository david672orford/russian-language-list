---
description: Word lists, grammatical data, and dictionaries in computer-readable formats
---
## Downloadable Linguistic Data
* [Modern Russian Frequency List](http://www.artint.ru/projects/frqlist/frqlist-en.php) --
	Serge Sharoff's word frequency list based on a selection of works
	in modern Russian
* [Zaliznayak's Morphological Dictionary](http://starling.rinet.ru/download/dicts.EXE) --
	This file is the basis for many implementations of Russian morphology.
	It contains the word entries from an early edition of Zaliznyak's
	morphological dictionary, though some of the unusual characters used
	in the printed dictionary have been replaced with ASCII substitutes.
	It does not include the information needed to interpret these entries.
	For that you must refer to printed dictionary or [scans](http://zaliznyak-dict.narod.ru/).)
	Though this is ostensibly a text file, it is stored in what is now a very
	inconvenient format:
	* It is an installer which runs under Microsoft Windows to install the text files.
	* The files it creates are encoded in the ALT encoding for MS-DOS which is now little used.
	* The already obscure ALT encoding is altered to provide accented vowels
	at code points usually used for graphic characters
	* The files contain typographical errors from the OCR process
	* At the end of each line a control-d character has been added followed by what is appearently
	intended as an English translation of the word, but these are often
	unintelligible.
	For these reasons you would likely do better to use Odict.
* [Odict.ru](http://odict.ru) --
	An expanded version of Zaliznyak's dictionary which (as of April
	2019) is being regularly updated. Users can contribute new word entries
	using a web interface. Includes documentation of the format taken from
	the forward to Zaliznayak's dictionary and adapted:
  * [Значение помет](http://odict.ru/pomety/)
  * [Формат статьи "грамматического словаря"](http://odict.ru/format/)
  * [Структура словаря (проект)](http://odict.ru/structure/)
* [Opencorpa](http://opencorpora.org) --
	A Russian corpus with ambiguity resolved so that the identity of each
	word and its morphological form is known
* [OPUS--an Open Source Parallel Corpus](http://opus.nlpl.eu/) --
	Translated texts sentence aligned. Can be searched on this and other
	sites. Datasets can be downloaded so that you can use them with your
	own tools. Texts come from sources including UN documents,
	government publications, Wikipedia, movie subtitles, and multilingual
	news sites.
* [Openrussian.org](https://en.openrussian.org/dictionary) --
    Database dumps of the Openrussian.org dictionary

## Programs for Russian Morphology
* [Pymorphy2](https://github.com/kmike/pymorphy2) --
	Morphological analyzer and inflection engine for the Russian
	and Ukrainian languages. Is of good quality, fast, but does not
	provide information about stressed syllables.
* [Jurta](http://www.jurta.org/en/node/71) --
	A program written in Perl which takes the entries in Zalizyak's
	dictionary and produces the full paradigm of each word. Unfortunately
	the author has not posted all of the files, so the program does not really
	work. The output files are posted though and these may be useful.
* [Russress](https://pypi.org/project/russtress/) --
	Uses a statistical model to guess the stress of Russian words in context

## Natural Language Processing in Russian
* [NLTK4RUSSIAN](http://mathling.phil.spbu.ru/node/160) --
	The [Natural Language Toolkit](http://www.nltk.org/) adapted for Russian
* [Natasha](https://github.com/natasha/natasha) --
	Rule-based named entity recognition library for Russian
* [Polyglot](https://pypi.org/project/polyglot/) --
	NLP library in Python with support for dozens to hundreds of languages,
	depending on the function
* [Link Grammar](https://github.com/opencog/link-grammar) --
	Natural language parser with support for Russian

## English Inflection
* [Pattern.en](https://www.clips.uantwerpen.be/pages/pattern-en)
* [Inflect](https://pypi.org/project/inflect/)

## Wordnet
* [The dictionary I use in my code](https://medium.com/broken-window/the-power-of-wordnet-with-nltk-7c45b20f52cf)
* [Extended Open Multilingual Wordnet](http://compling.hss.ntu.edu.sg/omw/summx.html)

## Other Lists
* [Обработка естественного языка. Полезные инструменты](https://www.pvsm.ru/python/13305/print/)
* [ru-eval: оценка методов автоматического анализа текстов](https://ru-eval.github.io/resources.html)

