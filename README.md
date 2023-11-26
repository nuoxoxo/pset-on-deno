__Run with the Bash script__
```
✗ sh denorun.sh day{1|2|...|10|...}
or
✗ sh typerun.sh day{1|2|...|11|...}
```
__Vanilla TypeScript__
```
✗ npm i @types/node axios dotenv
✗ tsc template.ts && node template.js
```
__Deno__
```
✗ curl -fsSL https://deno.land/x/install/install.sh | sh
✗ export AOC_SESSION=abc123
✗ which deno
✗ printenv
✗ deno run --allow-read --allow-env --allow-net template_deno.ts
```
