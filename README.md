# Illustrates what is happening when installing shrinkwrap

## Setup

- `async` dependency in package.json and shrinkwrap
- `mocha` devDependency in package.json and shrinkwrap
- `lodash` dependency in package.json only
- `chai` devDependency in package.json only

## Scenarios

### scenario1

Runs only `npm install`.

### scenario2

Sets `NODE_ENV` to production.

### scenario3

Sets `NODE_ENV` to test.

### scenario4

With `--no-shrinkwrap` option

### scenario5

With `--produciton` option
