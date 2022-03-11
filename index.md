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
`int x = 1`
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
   To access images in image assets you type `image literal` and then click on it. You should them be able to pick and look through all of your image assets
                          
---
#45 How to Solve the Error: "Maximum number of apps for free development reached"
How to solve app limit issue
---

#46. [Swift Deep Dive] Constants, the Range Operator and Randomisation

Use "let" to signify a constant value that cannot change or is hard to change
`let pi = 3.14259`

string("abc"), int(5), float(2.3), double(3.138483439) (double the decimals of float), bool(true/false) are all data types
Int.random(in: lower...upper) are how you create psudeo random numbers that are inclusive of 1 and 3. The three dots in that code are called a closed range oeprator
Int.random(in:lower..<upper) is an example of the possibilites of random numbers that include from the lower to upper-1 (doesnt include upper)
You can change the data type in the beginning to change random number outco

