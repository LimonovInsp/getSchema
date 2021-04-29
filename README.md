# getSchema

Implement a function that accepts an object and returns its properties data types
``` javascript
function getSchema(schema) {
  // write code
}

const schema = {
  version: 20,
  name: 'Aqua 2000',
  released: true,
  creator: { name: 'Chickchapukcha' },
};

console.log(getSchema(schema));  /* expected to be {
  version: 'number',
  name: 'string',
  released: 'boolean',
  author: 'object',
} */

```
