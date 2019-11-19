<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
</p>

# GraphQL Tooling Workshop 🛠

Welcome to the online GraphQL tooling workshop! We're really glad that you're here. Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

**Slides**

- [Graph Manager Student Challenge](https://slides.com/moonhighway/graph-manager/)
- [TypeScript & GraphQL](https://slides.com/moonhighway/typescript-graphql)

**Samples**

- [TypeScript & Apollo CLI - Finished Project + Step by Step](https://github.com/graphqlworkshop/snowtooth-typescript)
- [Snowtooth API](https://snowtooth.moonhighway.com)
- [Lift Manager Sample Client Code](https://github.com/eveporcello/lift-manager/blob/master/src/index.js)
- [Lift Manager Website](https://lift-manager.netlify.com)
- [Big Basin Sample Client Code](https://github.com/eveporcello/big-basin/blob/master/src/index.js)
- [Big Basin Website](https://big-basin.netlify.com)
- [Snowtooth Project Repo](https://github.com/moonhighway/snowtooth)
- [Client Side Mocking - CodeSandbox](https://codesandbox.io/s/client-mocking-epqmp)
- [Apollo REST Data Sources](https://github.com/MoonHighway/countries-datasources)
- [Batch Link](https://github.com/eveporcello/batching)

**Resources**

- [Graph Manager - Docs](https://www.apollographql.com/docs/graph-manager/)
- [Graph Manager Website](https://engine.apollographql.com)
- [TypeScript & Apollo - Apollo Docs](https://www.apollographql.com/docs/react/development-testing/static-typing/)
- [React TypeScript Cheatsheets](https://github.com/typescript-cheatsheets/react-typescript-cheatsheet)
- [TypeScript Playground](https://www.typescriptlang.org/play/index.html)

**Commands to Copy/Paste**

_Sample Engine API Key_

`ENGINE_API_KEY=service:eveporcello-6318:RQYT_LtqhrYG8Taw7ORtzA`

_Download the Schema_

`npx apollo schema:download --endpoint=https://snowtooth.moonhighway.com graphql-schema.json`

_Generate Types_

`npx apollo codegen:generate --localSchemaFile=graphql-schema.json --target=typescript --includes=src/**/*.ts --tagName=gql --addTypename --globalTypesFile=src/types/graphql-global-types.ts types`
