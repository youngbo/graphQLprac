# graphQLprac

A practice or study project for Stephen Grider's [GraphQL + React Udemy course](https://www.udemy.com/course/graphql-with-react-course/)

## Getting Started

* `npm install`

## Changelog

The main changes (where the original repo & this differ) are as follows:
* Updated libraries:
  - `react-apollo` is no longer used.  Related binds have been migrated directly into `@apollo/client`
  - `react`, `react-dom` now on the latest version
  - Development dependencies (ie. `babel`, `webpack` .. etc) are now updated to latest possible versions.
* Babel configuration has been been moved to the `webpack.config.js` file (see `babel-loader` settings)
* Fix deprecated APIs
  - `express-graphql`'s exports
  - `body-parser` json parsing is deprecated (functionality moved to `express`)

## Reference 
https://www.apollographql.com/docs/react
https://github.com/StephenGrider/GraphQLCasts
https://github.com/stephenGrider/lyrical-graphQL
https://github.com/vinnyA3/lyrical-graphql-deux
https://defineall.tistory.com/1004