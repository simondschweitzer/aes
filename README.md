# aes
AES - Ancient Egyptian Sentences; Corpus of Ancient Egyptian sentences for corpus-linguistic research

This corpus contains more than 100,000 sentences in transcription, translation, lemmatization, and partly with Hieroglyphic and morpho-syntactical encodings.

## source
[AED-TEI](https://github.com/simondschweitzer/aed-tei), a corpus of more than 11,000 Ancient Egyptian texts, which is based on [Teilauszug der Datenbank des Vorhabens "Strukturen und Transformationen des Wortschatzes der ägyptischen Sprache" vom Januar 2018](https://nbn-resolving.org/urn:nbn:de:kobv:b4-opus4-29190) with contributions of Burkhard Backes, Susanne Beck, Anke Blöbaum, Angela Böhme, Marc Brose, Adelheid Burkhardt, Roberto A. Díaz Hernández, Peter Dils, Roland Enmarch, Frank Feder, Heinz Felber, Silke Grallert, Stefan Grunert, Ingelore Hafemann, Anne Herzberg, John M. Iskander, Ines Köhler, Maxim Kupreyev, Renata Landgrafova, Verena Lepper, Lutz Popko, Alexander Schütze, Simon Schweitzer, Stephan Seidlmayer, Gunnar Sperveslage, Susanne Töpfer, Doris Topmann, Anja Weber

## licence
All files: [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

## encoded information
The textual data is encoded within sentences. Each sentence contains the following metadata information
- text: ID of the text containing this sentence. The ID links to the AED-TEI. E.g. The ID YNKBRPSSKZDHBPX3TGPWVKFRP4 refers to the text YNKBRPSSKZDHBPX3TGPWVKFRP4 you can find in AED-TEI with this ID, e.g. at https://github.com/simondschweitzer/aed-tei/blob/master/files/YNKBRPSSKZDHBPX3TGPWVKFRP4.xml 
- owner: the editor of the text (Burkhard Backes, Susanne Beck, Anke Blöbaum, Angela Böhme, Marc Brose, Adelheid Burkhardt, Roberto A. Díaz Hernández, Peter Dils, Roland Enmarch, Frank Feder, Heinz Felber, Silke Grallert, Stefan Grunert, Ingelore Hafemann, Anne Herzberg, John M. Iskander, Ines Köhler, Maxim Kupreyev, Renata Landgrafova, Verena Lepper, Lutz Popko, Alexander Schütze, Simon Schweitzer, Stephan Seidlmayer, Gunnar Sperveslage, Susanne Töpfer, Doris Topmann, or Anja Weber)
- corpus: subcorpus of Egyptian texts, e.g. \"sawlit\" for literary texts or \"bbawbriefe\" for letters
- date: date of the text; for the possible values cf. http://doi.org/10.5281/zenodo.3581069 
- findspot: findspot of the texts; for the possible values cf. http://doi.org/10.5281/zenodo.3581069 
- sentence translation: translation of the sentence, translated by the editor
Each sentence contains at least one word form. Every word form can contain several properties. Two properties are necessary:
- id: ID of the word form
- written form: Egyptological transcription of the word in Unicode
Some properties are optional:
- mdc: Egyptological transcription of the word in MdC
- line count: line count of the word
- lemma ID: ID of the Egyptian lemma (= lexical entry of the Egyptian word) in the AED (http://simondschweitzer.github.io/aed) to which the word form belongs
- lemma form: Egyptological transcription (Unicode) of the Egyptian lemma (= lexical entry of the Egyptian word) in the AED (http://simondschweitzer.github.io/aed) to which the word form belongs
- cotext translation: translation of the word form
- hieroglyphic encoding: Hieroglyphic writing of the word form encoded with Gardiner numbers (only if the writing of the word form is complete!)
- hieroglyphic encoding in Unicode: Hieroglyphic writing of the word form encoded with Unicode (only if the writing of the word form is complete!)
- hieroglyphic inventar: inventar of the hieroglyphs used in the writing of the word form; encoded with Gardiner numbers
Finally, there are some pos tags. Check the JSON schema for more details.

## data transformation, schema
by Simon D. Schweitzer, 2020-2021
