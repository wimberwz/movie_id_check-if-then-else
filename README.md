 

# Movie ID check


## Step 1

In this tuorial, we will create a program that checks to see if a user is old enough to enter a pg13 movie: Super Turdinator3: Bloodfest


## Step 2
Let's start by creating a "splash" to ask the user's age. 

```blocks
game.splash("Please enter your age")
```


## 3
Create an "Age" variable and set it to 0 at start. 
```blocks
let age = 0
```


##4
Let's modify our age variable to store the answer they give. 

```blocks
game.splash("Please enter your age")
let age = game.askForNumber("")
```

##5
Make a new Splash to say the information we stored. 

### ~ Since they entered a number, we must convert to text to "Say" it. 
```blocks
game.splash("Please enter your age")
let age = game.askForNumber("")
game.splash(convertToText(age))
```


##6
Great but we actually need to check if we can admit them, which we can do as a Number. Add an if statement, and the logic to "COMPARE" if they 13 or over. 
```blocks
game.splash("Please enter your age")
let age = game.askForNumber("")
if (age >= 13) {
    game.splash("Please enjoy the show")
}

```
##7
Now what should we say if they're not 13 or over?
```blocks
game.splash("Please enter your age")
let age = game.askForNumber("")
if (age >= 13) {
    game.splash("Please enjoy the show")
} else {
    game.splash("Sorry, you are not permitted to see the show")
}
```

##7
Great now run and test your program!

##8

**Your turn:** 

Replace the "Splash" screens with a nice sprite, so we have someone to talk to. 
```blocks
/**
 * replace "Splash" with sprite
 */
```



```ghost
let mySprite = sprites.create(img`
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
`)
mySprite.say(":)")
```




##9
If you understood everything
Proceed to the next Part of the module!
  
ELSE: ASK for help :)




...
