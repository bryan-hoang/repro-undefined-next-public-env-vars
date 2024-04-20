# repro-undefined-next-public-env-vars

This Next.js project reproduces an issue where `NEXT_PUBLIC_*` environment
variables that are defined as empty strings are evaluated as `undefined` rather
than an empty string.

To reproduce the issue:

```console
pnpm install
pnpm run dev
```
