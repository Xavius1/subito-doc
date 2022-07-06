<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-connector-mongodb](./subito-connector-mongodb.md) &gt; [Paginator](./subito-connector-mongodb.paginator.md)

## Paginator class

Class to implements the cursor paginator pattern

<b>Signature:</b>

```typescript
declare class Paginator implements IPaginator 
```
<b>Implements:</b> IPaginator

## Remarks

Specs by relayjs [https://relay.dev/graphql/connections.htm](https://relay.dev/graphql/connections.htm) Default cusor is based on the "createdAt" field, you can anything that sortable &amp; unique as "slug"

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)({ first, last, before, after, filters, })](./subito-connector-mongodb.paginator._constructor_.md) |  | Constructs a new instance of the <code>Paginator</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [currentPage](./subito-connector-mongodb.paginator.currentpage.md) | <code>protected</code> | number |  |
|  [field](./subito-connector-mongodb.paginator.field.md) | <code>protected</code> | string |  |
|  [filters](./subito-connector-mongodb.paginator.filters.md) | <code>protected</code> | IFilterPipelineInput |  |
|  [hasNextPage](./subito-connector-mongodb.paginator.hasnextpage.md) | <code>protected</code> | boolean |  |
|  [hasPreviousPage](./subito-connector-mongodb.paginator.haspreviouspage.md) | <code>protected</code> | boolean |  |
|  [limit](./subito-connector-mongodb.paginator.limit.md) | <code>protected</code> | number |  |
|  [order](./subito-connector-mongodb.paginator.order.md) | <code>protected</code> | PaginatorOrder |  |
|  [totalPage](./subito-connector-mongodb.paginator.totalpage.md) | <code>protected</code> | number |  |
|  [totalResults](./subito-connector-mongodb.paginator.totalresults.md) | <code>protected</code> | number |  |
|  [type](./subito-connector-mongodb.paginator.type.md) | <code>protected</code> | [ParseType](./subito-lib.parsetype.md) |  |
|  [value](./subito-connector-mongodb.paginator.value.md) | <code>protected</code> | string \| null |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [get(docs)](./subito-connector-mongodb.paginator.get.md) |  | Get the paginator result |
|  [getDocCursor(doc)](./subito-connector-mongodb.paginator.getdoccursor.md) |  | Get the cursor value from a doc |
|  [getPipeline(customPipeline, reverse)](./subito-connector-mongodb.paginator.getpipeline.md) |  | Get the pipeline to use for the aggregation |
|  [setCursor({ field, type })](./subito-connector-mongodb.paginator.setcursor.md) |  | Set a custom cursor |
|  [setPageInfo({ total, cursored })](./subito-connector-mongodb.paginator.setpageinfo.md) |  | Define page info from results |
