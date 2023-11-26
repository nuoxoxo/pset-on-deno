__Run with the Bash script__
```
✗ sh denorun.sh day{1|2|...|10|...}
or
✗ sh typerun.sh day{1|2|...|11|...}
```
__Vanilla TypeScript__
###### ﹥ token required inside .env 
```
✗ npm i @types/node axios dotenv
✗ tsc template.ts && node template.js
```
__Deno__ 
<img src='https://deno.com/images/artwork/HypnoDeno.gif?__frsh_c=dad2' width='12px' />
###### ﹥ export the token 
```
✗ curl -fsSL https://deno.land/x/install/install.sh | sh
✗ export AOC_SESSION=abc123
✗ which deno
✗ printenv
✗ deno run --allow-read --allow-env --allow-net template_deno.ts
```

<img src='https://deno.com/images/artwork/hashrock_simple.png?__frsh_c=dad21828de649d12df5a23c572b88f3a3a73d0dc' width='42px' />
