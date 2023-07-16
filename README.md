# bashword-words

This is a simple GitHub Pages site with dictionary words for use with
[bashword][1] --- a pure Bash password/passphrase generator.

Download and verify the word list:

```sh
wget https://itspriddle.github.io/bashword-words/words.gz
wget https://itspriddle.github.io/bashword-words/words.sha256
shasum -c words.sha256
```

[1]: https://github.com/itspriddle/bashword
