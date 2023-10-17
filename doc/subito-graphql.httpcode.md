<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [subito-graphql](./subito-graphql.md) &gt; [httpCode](./subito-graphql.httpcode.md)

## httpCode variable

List of http code

**Signature:**

```typescript
httpCode: {
    readonly OK: 200;
    readonly CREATED: 201;
    readonly ACCEPTED: 202;
    readonly NO_CONTENT: 204;
    readonly NEED_ACTION: 290;
    readonly BAD_REQUEST: 400;
    readonly UNAUTHORIZED: 401;
    readonly FORBIDDEN: 403;
    readonly NOT_FOUND: 404;
    readonly CONFLICT: 409;
    readonly GONE: 410;
    readonly INTERNAL_SERVER_ERROR: 500;
    readonly NOT_IMPLEMENTED: 501;
}
```

## Remarks

Use UNAUTHORIZED when the action need an authentification and the viewer is a guest Use FORBIDDEN when the user is auth but he has no rights
