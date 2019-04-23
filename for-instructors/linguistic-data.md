## Downloadable Linguistic Data
* [Modern Russian Frequency List](http://www.artint.ru/projects/frqlist/frqlist-en.php)
	--Serge Sharoff's word frequency list based on a selection of works
	in modern Russian
* [Opencorpa](http://opencorpora.org)
	--A Russian corpus with ambiguity resolved so that the identity of each
	word and its morphological form is known
* [Zaliznayak's Morphological Dictionary](http://starling.rinet.ru/download/dicts.EXE)
	--This file is the basis for many implementations of Russian morphology.
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
* [Odict.ru](http://odict.ru)
	--An expanded version of Zaliznyak's dictionary which (as of April
	2019) is being regularly updated. Users can contribute new word entries
	using a web interface. Includes documentation of the format taken from
	the forward to Zaliznayak's dictionary and adapted:
  * [Значение помет](http://odict.ru/pomety/)
  * [Формат статьи "грамматического словаря"](http://odict.ru/format/)
  * [Структура словаря (проект)](http://odict.ru/structure/)

## Programs for Using Linguistic Data
* [Pymorphy2](https://github.com/kmike/pymorphy2)
	--Morphological analyzer and inflection engine for the Russian
	and Ukrainian languages. Is of good quality, fast, but does not
	provide information about stressed syllables.
* [Jurta](http://www.jurta.org/en/node/71)
	--A program written in Perl which takes the entries in Zalizyak's
	dictionary and produces the full paradigm of each word. Unfortunately
	the author has not posted all of the files, so the program does not really
	work. The output files are posted though and these may be useful.

