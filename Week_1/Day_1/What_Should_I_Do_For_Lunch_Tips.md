### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in your terminal.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

``` Javascript 
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("Get back to work!");
  } else if (hungry === true && availableTime < 20) {
    console.log("Pick something up and eat it in the lab");
  } else if (hungry === true && availableTime < 30) {
    console.log("Try a place near by");
  } else if (hungry === true && availableTime > 30) {
    console.log("Remember you are in a bootcamp with not much time to spare");
  }
};
```
