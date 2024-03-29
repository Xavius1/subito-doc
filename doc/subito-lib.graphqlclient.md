<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-lib](./subito-lib.md) &gt; [GraphqlClient](./subito-lib.graphqlclient.md)

## GraphqlClient class

Connect to a GraphQL endpoint

**Signature:**

```typescript
declare class GraphqlClient implements IGraphqlClient 
```
**Implements:** [IGraphqlClient](./subito-lib.igraphqlclient.md)

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)({ endpoint, headers, authQuery, })](./subito-lib.graphqlclient._constructor_.md) |  | Constructs a new instance of the <code>GraphqlClient</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [authQuery](./subito-lib.graphqlclient.authquery.md) | <code>protected</code> | string | Auth query |
|  [client](./subito-lib.graphqlclient.client.md) | <code>protected</code> | GraphQLClient | The graphql client |
|  [expirationDate](./subito-lib.graphqlclient.expirationdate.md) | <code>protected</code> | number | The token expiration date |
|  [input](./subito-lib.graphqlclient.input.md) | <code>protected</code> | [AuthInput](./subito-lib.authinput.md) | The credentials to auth the client |
|  [token?](./subito-lib.graphqlclient.token.md) | <code>protected</code> | string \| null | _(Optional)_ The auth token |
|  [viewerToken?](./subito-lib.graphqlclient.viewertoken.md) | <code>protected</code> | string \| null | _(Optional)_ The auth viewer token |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [auth(input)](./subito-lib.graphqlclient.auth.md) |  | Get an auth token |
|  [execute(query, input)](./subito-lib.graphqlclient.execute.md) |  | Execute a query through the graphql endpoint |
|  [getClientName()](./subito-lib.graphqlclient.getclientname.md) |  | Get the client name |
|  [isTokenExpired()](./subito-lib.graphqlclient.istokenexpired.md) | <code>protected</code> | Check if the token has expired |
|  [refreshAuth()](./subito-lib.graphqlclient.refreshauth.md) | <code>protected</code> | Get a new auth token |
|  [setAuthHeaders()](./subito-lib.graphqlclient.setauthheaders.md) | <code>protected</code> | Set auth headers |
|  [setCustomHeaders(headers)](./subito-lib.graphqlclient.setcustomheaders.md) |  | Set custom headers |
|  [setExpirationDate(date)](./subito-lib.graphqlclient.setexpirationdate.md) | <code>protected</code> | Set expiration date |
|  [setViewerToken(token)](./subito-lib.graphqlclient.setviewertoken.md) |  | Set viewer token |

