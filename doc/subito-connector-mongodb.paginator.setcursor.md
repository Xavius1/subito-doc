<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-connector-mongodb](./subito-connector-mongodb.md) &gt; [Paginator](./subito-connector-mongodb.paginator.md) &gt; [setCursor](./subito-connector-mongodb.paginator.setcursor.md)

## Paginator.setCursor() method

Set a custom cursor

**Signature:**

```typescript
setCursor({ field, type }: ICursor): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  { field, type } | [ICursor](./subito-connector-mongodb.icursor.md) |  |

**Returns:**

this


## Example


```
// Use the "slug" field as cursor
paginator.setCursor({ field: 'slug', type: 'string' });
```

