# music-manager

> Manages a list of favorite artists and opens playlists on youtube.

Listen to music daily but are too lazy to pick an artist, lazy to even come up with one, always end up listening to the same four artists over and over again? `mm` is for you.

# install

use npm.

```shell
npm i -g music-manager
```

you get `mm` as a cli.

# usage

```shell
» mm
usage:
  mm <command> [argument]

commands:
  --add, -a <terms>             adds a term to the list of favorite artists.
  --add-random, --ar <category> adds 10 random artist suggestions from the provided category.
  --i <amount>                  defines how many random artist suggestions are added with `--ar` or shown with `-s`.
  --remove, --rm, -r <terms>    removes a term from the list of favorite artists. expects an exact match.
  --clear                       clears your list of favorite artists.
  --list, -l                    lists currently favorite artists.
  --suggest, -s [category]      suggests a random artist. you may provide a desirable category such as "rock".
  --open, -o                    opens youtube in your default browser at the search results page for a random artist.
  --best, -b                    flag for `--open`, searches for "best of" tracks.
  --long                        flag for `--open`, searches for longer tracks.
```

# license

mit
