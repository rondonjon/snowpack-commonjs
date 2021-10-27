This repository contains a demo to illustrate a problem with snowpack.

When the `css-select` library is directly imported, its named exports `selectOne` and `selectAll` are properly resolved.

When the `css-select` library is impored indirectly through `node-html-parser`, the named imports become `undefined` although `node-html-parser` uses the exact same import statements.

Usage:

- yarn install
- yarn start
