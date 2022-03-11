# Swift Udemy Notes 

#H1
##H2
###H3

*Italicized Text*
**Bold Text **

`code`
---
#42. [Swift Deep Dive] Variables
You can print out a string and a variable by using this format 
Make sure you have an equal amount of space between equal signs

`var a = 5`
`print("The value of a is \(a)")`

**Triangularing values**

`func exercise() {`

  `var a = 5`
    `var b = 8`
   
`var x = 0`

`x=b`

`b=a`

`a=x`

 `print("a: \(a)")`
 `print("b: \(b)")`
    
`}`
---
#43. [Swift Deep Dive] Arrays
int x = 1
`var numArray = [1, 2, 3, 4, 5] [x]`
 You can write arrays also in this format as x for the index of each element in the array 
`let numbers = [45, 73, 195, 53]`

  `let computedNumbers = [numbers[0] * numbers[1], numbers[1] * numbers[2], numbers[2] * numbers[3], numbers[3] * numbers[0]]`
    `print(computedNumbers)`

    
    
    
  
    
   
     ---
     
      #44. How to Randomise the Dice Images   
       If coding warnings have a white circle in them, it means Xcode things it knows how to fix the error
       
      `@IBOutlet wear var dinceImageView: UIImageView!`
      let diceArray = [1,2,3,4,5,6]`
    ` diceImageView.image = diceArray[Int.random(in:0...5)]` Another way to do this would be to do 
    ` diceImageView.image = diceArray.randomElement()
   
                          

