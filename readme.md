# delete-null

  Cleaning Objects was never more easy.

```js
const deleteNull = require('delete-null');

var obj = {
  name: "ribhu",
  surname: "ratnam",
  age: 20,
  bio: {},
  friends: {
    first : undefined,
    second : null
  },
  books: {
    first: "Harry Potter",
    second: {},
    third: null,
    fourth : undefined
  }
}

obj = deleteNull(obj);
  /*
  obj = {
    name: "ribhu",
    surname: "ratnam",
    age: 20,
    books: {
      first: "Harry Potter"
    }
  }
  */
```

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).
Node.js 0.10 or higher is required.

If this is a brand new project, make sure to create a `package.json` first with
the [`npm init` command](https://docs.npmjs.com/creating-a-package-json-file).

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```bash
$ npm install delete-null
```

## Features

  * Handles null
  * Handles empty objects
  * Handles undefined values
  * Fast & recursive


## Philosophy

  
  While dealing with objects, we often have to write code to handle null or empty objects or undefined values. This package will handle all that, giving you an Object that doesn't contain unwanted values.


## People

Author of delete-null is [Ribhu Ratnam](https://github.com/ribhuji).

Visit [Ribhu's website](https://ribhuji.github.io/ribhu/) for contact.

## License

  [MIT](LICENSE)
