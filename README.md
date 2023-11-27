# PyDictionary
Python wrapper over the Free Dictionary API

```python
from PyDictionary.PyDictionary import pyDictionary

pydictionary = pyDictionary.PyDictionary(word="world")
definitions, synonyms = pydictionary.get_meanings(partOfSpeech="noun")
audio = pydictionary.getAudio()
dictionary = pydictionary.getDictionary()
```
