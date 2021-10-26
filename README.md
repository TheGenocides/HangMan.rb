# HangManGames

[HangMan](https://www.google.com/search?q=what+hangman+game&rlz=1C1CHBD_enID925ID925&oq=Whats+hangman&aqs=chrome.1.0i512j0i22i30l4j0i10i22i30l2j0i22i30l3.2724j0j4&sourceid=chrome&ie=UTF-8) is a paper and pencil guessing game for two or more players. One player thinks of a word, phrase or sentence and the other(s) tries to guess it by suggesting letters within a certain number of guesses. I was inspired by [this](https://github.com/dbattersby/ruby-hangman) Repo, So i'm Re-making this game with more features and some from the repo itself, i hope you like it!

# Usage
```bash
$ git clone https://github.com/TheGenocides/HangMan.rb
```

```bash
$ cd HangMan.rb 
```

Open your IRB
```rb
require_relative "hangman.rb"

hang=HANGMAN::HangMan.new
hang.start
```

# Note

There is only 5 question in this game, you can add more by contributing to our [Github](https://github.com/TheGenocides/HangMan.rb)