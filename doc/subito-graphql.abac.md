<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-graphql](./subito-graphql.md) &gt; [Abac](./subito-graphql.abac.md)

## Abac class

Abstract class to implements Abac control Initialize as data sources to have context

<b>Signature:</b>

```typescript
declare abstract class Abac 
```

## Example


```
class MyAbac extends Abac {
  public Entity: EntityAbac
}
```
Then into index.ts

```
dataSources: () => ({
  abac: new MyAbac()
})
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [context](./subito-graphql.abac.context.md) | <code>protected</code> | null |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [initialize({ context, })](./subito-graphql.abac.initialize.md) |  |  |
