# Ferret Keywords

## Core Declarations
```
let       // variable declaration
const     // immutable binding
struct    // define a struct
fn        // define a function
interface // define an interface
enum      // define an enum
```

## Control Flow
```
if
else
for
while
break
continue
when      // replaces match
```

## Special Values
```
true
false
null
```

## Memory / Scope
```
defer     // run when scope exits
```

## Modules / Imports
```
import
export
```

## Error Handling
```
catch     // catch block for T! functions
```

## Miscellaneous
```
as        // type cast
return    // replaces ret
spawn     // start coroutine
```

**Notes:**
- Total keywords: 22
- `catch` is specifically for `T!` functions.
- `spawn` replaces Go-style coroutines.
- No `impl`, `default`, `try`, `throw`, `ret`, or `with`.
