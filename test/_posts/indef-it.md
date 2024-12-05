# Indefinite Iteration of Oxide
The loop keyword indicates an infinite loop. The break statement exits the loop and the continue keyword skips the rest of the iteration and starts a new one.

Examples:
```
loop {
    	count += 1;

    	if count == 3 {
          continue;
    	}

    	if count == 5 {
          break;
    	}
}
```

```
let counter:i32 = 0;
let result:i32 = 0; 

loop {
  counter += 1;
  if counter == 10 {
    result = counter * 2;
    break;
  }
};
```
