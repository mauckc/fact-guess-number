# fact-guess-number
Telegram Bot for guessing a number and returning hints and facts.
Using async and using calls to numbersapi

### Requrements
Using python 3.5+
using telepot package

install with pip via:

```
$ pip install telepot
```

```
$ python3.5 factguessa.py <token>
```

### Bot Logic Structure
Guess a number:
1. Send the bot anything to start a game.
2. The bot randomly picks an integer between 0-99.
3. You make a guess.
4. The bot tells you to go higher or lower.
5. Repeat step 3 and 4, until guess is correct.
