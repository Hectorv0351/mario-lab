## Itsa me, Mario!

Toward the beginning of World 1-1 in Nintendo’s Super Mario Brothers, Mario must hop over two "half-pyramids" of blocks as he heads toward a flag pole. Below is a screenshot.

![mario](http://www.infendo.com/wp-content/uploads/2008/06/mario.png)

Your mission is to recreate these blocks using code. 

### Part I: The Boring Pyramid
Create a program that will print the following pyramid:

```
   #  #
  ##  ##
 ###  ###
####  ####
```

(The height and the width of the half-pyramids pictured above are 4 with a gap of size 2 separating them.) 

### Part II: User Specified Height

Add a new feature to your program that asks a user how tall they would like to make the pyramid. This should be a non-negative integer no greater than 23 (this is the tallest that a pyramid can be in Mario land).

Hint: use `.repeat()`

Javascript example:
```js
console.log("You are " + "so ".repeat(5) + "awesome!");
// You are so so so so so awesome!
```

Java example: 
```java
System.out.println("You are " + "so ".repeat(5) + "awesome!");
// You are so so so so so awesome!
```

### Part III: Chained pyramids

Modify your code to prompt the user for the number of pyramids they want. Using this number, stack the pyramids on top of each other in a chain. This would be an example of a pyramid with height of 4 and chain length of 3:
```
   #  #
  ##  ##
 ###  ###
####  ####
   #  #
  ##  ##
 ###  ###
####  ####
   #  #
  ##  ##
 ###  ###
####  ####
```
### Part IV: Every-Other-Upside-Down Pyramid
Modify your code to make every other pyramid inverted. Example:
```
   #  #
  ##  ##
 ###  ###
####  ####
####  ####
 ###  ###
  ##  ##
   #  #
   #  #
  ##  ##
 ###  ###
####  ####
```
