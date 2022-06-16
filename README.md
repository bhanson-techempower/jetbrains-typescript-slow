# Demo project to reproduce TypeScript slowness with JetBrains IDEs

Open `tests/test.ts` in WebStorm or IntelliJ and type:

```typescript
expect('').
```

And wait. On my machine it takes 4-7 seconds to open.