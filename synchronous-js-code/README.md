This is an example of synchronous code.

We can see that the input is printed on the console only after it is read from input.txt

This is because fs.readFileSync() statement blocks the execution of code. The complete program will wait for this line before executing any furthur lines below it.

This is also known as blocking-synchronous js code.
