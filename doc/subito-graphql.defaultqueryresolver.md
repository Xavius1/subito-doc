<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-graphql](./subito-graphql.md) &gt; [DefaultQueryResolver](./subito-graphql.defaultqueryresolver.md)

## DefaultQueryResolver variable

Define default query resolvers

Can be use as is or extended in a custom resolver

**Signature:**

```typescript
DefaultQueryResolver: (source: string) => {
    getOne({ id, type }: GetOneProps, context: AnyObject): Promise<any>;
    getMany(args: AnyObject, context: AnyObject): Promise<any>;
    getAll(args: AnyObject, context: AnyObject): Promise<any>;
}
```
