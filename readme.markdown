# music-manager

> Manages a list of favorite artists and opens playlists on youtube.

Listen to music daily but are too lazy to pick an artist, lazy to even come up with one, always end up listening to the same four artists over and over again? `mm` is for you.

# install

use npm.

```shell
npm i -g music-manager
```

you get `mm` as a cli.

# `mm --add "many terms"` or `mm -a term`

adds a term to the list of favorite artists.

# `mm --remove "many terms"` or `mm --rm "many terms"` or `mm -r term`

removes a term from the list of favorite artists. expects an exact match.

# `mm --clear`

clears your list of favorite artists.

# `mm --list` or `mm -l`

lists currently favorite artists.

# `mm --suggest "category terms"` or `mm -s category`

displays a random artist suggestion from the provided category _(e.g: `rock`)_. you can omit the category filter.

```shell
mm -s "punk rock"
Angelic Upstarts
```

# `mm --add-random "category terms" -i 10` or `mm --ar category -i 10` or `mm --ar`

adds `10` random artist suggestions from the provided category _(e.g: `rock`)_. you can omit the category filter. you can change `10` to any number using the `-i` parameter.

# `mm --open` or `mm -o`

opens youtube in your default browser at the search results page for a random artist. there are some flags that can tweak behavior.

| flag                | description                                                     |
|---------------------|-----------------------------------------------------------------|
| `--best` or `-b`    | display search results for `best of <artist>`                   |
| `--long`            | display search results for `<artist> hours`; gets longer videos |
| `--suggest` or `-s` | display search results for a suggested artist                   |

# license

mit
