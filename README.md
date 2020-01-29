# vti test

Run `npm run vti`
I'm getting error:

```
Argument of type '{ setup(): { test: Ref<number>; }; }' is not assignable to parameter of type 'new (...args: any[]) => any'.
  Type '{ setup(): { test: Ref<number>; }; }' provides no match for the signature 'new (...args: any[]): any'
```

If remove `lang="ts"`, vti claims there are no errors. Obviously, it's not the case.