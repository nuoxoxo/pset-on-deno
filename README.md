# __Denon__ <img src='https://deno.com/images/artwork/HypnoDeno.gif?__frsh_c=dad2' width='24px' />
###### Denon is used here mainly for HMR 
Prep
```
✗ deno install --allow-read --allow-run -f https://deno.land/x/denon/denon.ts
```
denon.json
```
{
  "scripts": {
    "start": {
      "cmd": "deno run",
      "watch": true,
      "allow": ["read", "net", "env"],
      "ext": "ts",
      "unstable": true
    }
  }
}
```
Run
```
✗ denon start Filename.ts
```
# __Deno__  <img src='https://deno.com/images/artwork/hashrock_simple.png?__frsh_c=dad21828de649d12df5a23c572b88f3a3a73d0dc' width='24px' /> 
Run  
```
✗ sh deno.sh day{1|2|...|10|...}
```
Walk
###### We have to export the token 
```
✗ curl -fsSL https://deno.land/x/install/install.sh | sh
✗ export AOC_SESSION=abc123
✗ which deno
✗ printenv
✗ deno run --allow-read --allow-env --allow-net template_deno.ts
```

# __Node__
Run 
```
✗ sh node.sh day{1|2|...|11|...}
```
Walk
###### Token is required inside .env 
```
✗ npm i @types/node axios dotenv
✗ tsc template.ts && node template.js
```

&#8203;


