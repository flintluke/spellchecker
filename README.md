Spell Checker REST API
============
Work for course "Highload web-systems"

REST API:
* GET /spellchecker.com/word   - Get possible correct variants for spelled word. Count of variants is default.
                                          Variant must be sorted by probalility
* GET /spellchecker.com/word?count=N   - Same as previous, but count of possible correct variants is N
* POST /spellchecker.com/word   - Add new word to dictionary
* PUT /spellchecker.com/wordSpelled/wordCorrected  - Increase probability that if user typed word wordSpelled he meant wordCorrected
* DELETE /spellchecker.com/word - Remove word from dictionary
