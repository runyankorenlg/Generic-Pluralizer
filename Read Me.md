This generic pluralizer currently supports seven languages:
chiShona, isiXhosa, isiZulu, Kikuyu, Kinyarwanda, Luganda, and Runyankore
The language in which one is working must be stated.

Requirements: Java Runtime Environment

1. To pluralize a single word:
java GenericPluralizer <Language> <NounWithNC>
For Example:
java GenericPluralizer Runyankore omwana,1i

The noun class should be separated from the noun by a comma, as above

2. To pluralize several nouns in a text file:
java GenericPluralizer <Language> <TextFile>
For Example:
java GenericPluralizer isiZulu nouns.txt
The output will be written to <Language>_generated_plurals.txt, for example, "isiZulu_generated_plurals.txt"

See the accompanying datasets of singulars for the format of the input files.


