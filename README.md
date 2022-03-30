# run-run-run.js
run JS code from string

```
  const x = 2;
  const y = 3;
  
  console.log(run("x + y")); //evaluate
  console.log(runf("x + y")); //run as function
  console.log(runo({ x, y }, "x + y")); //run as function with named params
  console.log(runp("x", "+", "y")); //run with tokens
```
