1. calling puts on arguments nil, give bad message, "Argument is nil" ?? 
2. create loop with var without declare first, don't give feedback about error.
for (;;) {
	var token = l["nextToken"]();
}
3. expression: ERROR: object.call.function isnt callable. Got: *object.Null    
4. null.type() some weired error  
5. make function pointer to be available in future 
6. len() on HASH give error, but when is embebed inside a big deep function call, it give nothing as error, or is massive loop.   
7. ERROR: index operator not supported: ARRAY%  (where is line?)
8. sometime when deep in rabbit hole give an error, for loop don't catch and put infinite loop in action
9. check if a value isTruthy from nil 
goroutine 1 [running]:
ninja/object.IsTruthy({0x0, 0x0})
	/home/runner/work/ninja/ninja/object/object.go:62 +0x24
10. tool for print complete ast  
11. what is desire behavior for var a = 0; function add() { return function increment() { a++; return a; }}; var b = add()(); add()(); 1 or 2 or undefined variable a ?