Check app.spec.ts in apps/cypress-typing-e2e/src/integration to see missing typing for login command.

On run of test, you will get error:

```
ERROR in /Users/kramme/projects/github-issue-example-repos/cypress-typing-issue/apps/cypress-typing-e2e/src/integration/app.spec.ts(8,8):
TS2339: Property 'login' does not exist on type 'cy & EventEmitter'.
Version: typescript 4.1.5
```

