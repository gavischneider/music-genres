# Music Genres

A random music genre generator. Includes more than 220 subgenres spanning 13 different genres.

## Install

```javascript
npm i music-genres
```

## Example

```javascript
const musicGenres = require('music-genres');

musicGenres.getAllGenres();
// Returns all genres - an object holding genres

musicGenres.getRandomGenre();
// Returns random genre - an array holding subgenres

musicGenres.getRandomSubgenre();
// Returns random subgenre - a string
```
