# mongo-random-id
# install
```
yarn add mongo-random-id;
// or
npm insatall mongo-random-id;
```
# usage
```
import random form 'mongo-random-id';
// or
random = require('mongo-random-id');

random.id([n])
// Returns a unique identifier, such as "Jjwjg6gouWLXhMGKW", that is likely to be unique in the whole world. The optional argument n specifies the length of the identifier in characters and defaults to 17.

random.secret([n])
// Returns a random string of printable characters with 6 bits of entropy per character. The optional argument n specifies the length of the secret string and defaults to 43 characters, or 256 bits of entropy. Use random.secret for security-critical secrets that are intended for machine, rather than human, consumption.

random.fraction()
// Returns a number between 0 and 1, like Math.random.

random.choice(arrayOrString)
// Returns a random element of the given array or string.

random.hexString(n)
// Returns a random string of n hexadecimal digits.
```
# test
```
yarn run test
// or
npm run test
```
