# Playing Werewords with GPT-3

This a simple game to try to guess the secret word chosen by the script.

An example questionable conversation with Open AI


```
$ pipenv run ./play.py
Q: Is it a noun?
A:  Yes.
Q: Is it an animal?
A:  No.
Q: Is it alive?
A:  Yes.
Q: is it a plant?
A:  No, *** is not a plant.
Q: is it edible?
A:  Yes, *** is edible.
Q: Is it man-made?
A:  No.
Q: is it buyable?
A:  No.
Q: Is it sell in store?
A:  Yes, you can buy *** in the store.
Q: Is it costing under $10?
A:  No.
Q: hint
A: The word starts with: L
Q: hint
A: The word starts with: LU
Q: is it a candy?
A:  No.
Q: is it healthy?
A:  Yes, he's healthy.
Q: hint
A: The word starts with: LUC
Q: is it a cereal?
A:  No, *** is a game.
Q: hint
A: Answer is: LUCK
Stats(questions=12, guesses=0, hints=3)
```


## Getting started

1. Sign up for an OpenAI token at https://beta.openai.com/
2. Add the file into secrets.py
```
OPENAI_API_KEY = '<apikey>'
```


## Attribution

Word list is from the list at http://werewords.com/wordlister/display.php?a=486&b=5A44893D
