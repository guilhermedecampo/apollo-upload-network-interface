# apollo-upload-network-interface

UploadNetworkInterface for Apollo GraphQL Client. Adds support for `multipart/form-data` requests.

Used together with [graphql-server-express-upload](https://github.com/HriBB/graphql-server-express-upload) and [graphql-server-koa-upload](https://github.com/HriBB/graphql-server-koa-upload) (coming soon).

## Usage

```
import ApolloClient from 'apollo-client'
import createNetworkInterface from 'apollo-upload-network-interface'

const networkInterface = createNetworkInterface({
  uri: '/graphql',
})

const client = new ApolloClient({
  networkInterface
})
```

## TODO

- [ ] Add some tests
