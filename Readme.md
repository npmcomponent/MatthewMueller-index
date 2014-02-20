*This repository is a mirror of the [component](http://component.io) module [matthewmueller/index](http://github.com/matthewmueller/index). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewmueller-index`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# index

  simple indexing of strings for basic fuzzy search

## Example

```js
var index = Index(['apple', 'orange', 'pear']);

index.search('ang') // true
index.search('pp') // true
index.search('ppp') // false
```

## Installation

    $ component install matthewmueller/index

## API

### Index([words])

Initialize an `Index`, with an optional `words` array.

### index.add(words)

Add a string or array of `words` to the index.

### index.search(str)

Search for a string within the index. Returns `true` if the string is present, otherwise `false`.

## License

  MIT
