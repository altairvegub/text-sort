# Text-Sort
## Sentence Tokenizer & Alphabetical Sorter with customizable functionality

Default collation is base character sorting (case insensitive), followed by case priority (lowercase letters are under capitals) for tie breaking and by default ignores quotation marks.

To run the program you'll need NLTK https://www.nltk.org/install.html </br>
The program also requires the NLTK Data files and should automatically check and install them when you first run the program.
### Mac/Unix
```
pip install --user -U nltk
```

To run the tests you'll need Pytest
```
pip install -U pytest

pytest
```

Running the program

```
python3 text_sorter.py
```
