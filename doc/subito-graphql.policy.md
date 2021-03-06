<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-graphql](./subito-graphql.md) &gt; [Policy](./subito-graphql.policy.md)

## Policy class

Abstract class to implements Abac policy control

<b>Signature:</b>

```typescript
declare abstract class Policy 
```

## Example


```
class EntityPolicy extends Policy {
  read({ doc }) {
    if(this.hasRole['ADMIN']) {
      return doc;
    }
    return null;
  }
}
```
Then into a resolver

```
const { dataSources: { Abac } } = context;
Abac.EntityPolicy.read({ doc });
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)({ viewer, gateway })](./subito-graphql.policy._constructor_.md) |  | Constructs a new instance of the <code>Policy</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [gateway](./subito-graphql.policy.gateway.md) | <code>protected</code> | null | The current gateway |
|  [viewer](./subito-graphql.policy.viewer.md) | <code>protected</code> | [AnyObject](./subito-graphql.anyobject.md) \| null | The current viewer |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [create()](./subito-graphql.policy.create.md) |  | Check if a doc can be create, then throw if not |
|  [delete()](./subito-graphql.policy.delete.md) |  | Check if a doc can be deleted, then throw if not |
|  [hasRole(role)](./subito-graphql.policy.hasrole.md) | <code>protected</code> | Check if the current user has a role |
|  [isAdmin()](./subito-graphql.policy.isadmin.md) | <code>protected</code> | Check if the user is an admin |
|  [read(doc)](./subito-graphql.policy.read.md) |  | Read a doc |
|  [readMany(docs, keepNull)](./subito-graphql.policy.readmany.md) |  | Read an array of docs |
|  [readManyByCursor(docs)](./subito-graphql.policy.readmanybycursor.md) |  | Read a list of doc listed by cursor |
|  [update()](./subito-graphql.policy.update.md) |  | Check if a doc can be updated, then throw if not |

