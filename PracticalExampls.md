let see some practical example that will gave us more clearty 

```javascript

function add(a,b){
return a+b
}

console.log(add(2,5)) // 7

console.log(add(2,"Hello") // 2Hello 
```

In this exampls we can see  how a simple function can affect the 
output without type safety. 
The  funtion is built to work with numbers  but
a user's  string input also get processed and returns a string but we need a number 

```typescript
function add(a:number,b:number):number{
                return a+b
      }

console.log(add(2,5)) // 7

console.log(add(2,"Hello") // 2Hello   Typescript Error

```

In typescript code we can seee that it identify  type errror before runinig the code that helps to get error way before it affect the code  
. 
