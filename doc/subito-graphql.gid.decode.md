<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-graphql](./subito-graphql.md) &gt; [GID](./subito-graphql.gid.md) &gt; [decode](./subito-graphql.gid.decode.md)

## GID.decode() method

> Warning: This API is now obsolete.
> 
> Use the new [GID.read()](./subito-graphql.gid.read.md) method instead.
> 

Decode a global ID

**Signature:**

```typescript
static decode(gid: string, raw?: Boolean): string | number | {
        id: string | number;
        version: number;
        data: {};
        type: string;
    };
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  gid | string | GID to decode |
|  raw | Boolean | _(Optional)_ |

**Returns:**

string \| number \| { id: string \| number; version: number; data: {}; type: string; }


## Example

We want to build a GID to identify the third product save in cart Each cart are saved into a document containing an array of product

```
// Prints "12":
console.log(GID.decode('xxx'));
```

