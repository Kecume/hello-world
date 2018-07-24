# hello-world
This is my first repository.

Hi, my name is moon from galaxy. I always feel cold at night. 
When the sun appears, I will hide from his back.


//: Playground - noun: a place where people can play

import UIKit

var str = "Hello, playground"


var hp = 75
var x = hp/10 // 75/10=7
if hp == 0 {
    print("you're dead!")
} else if hp % 10 == 0 {
    print(hp)
} else if hp > 20 && hp <= 100 {
    print((x+1)*10)
} else if hp < 20 {
    print(20)    
}

//80


var y = 20
while y >= 10 {
    print ("Hellow,\(y)")
    x -= 2
}
//Hello,20
//hello,18
//Hello,16
//Hello,14
//Hello,12





let myInt = 1
var desc = "The number \(myInt) is"
switch myInt {
case 1,4,6,7,8,9,100 :
    desc += " an essential number, and also"
    fallthrough
default:
    desc += " an integer."
}

print(desc) 1 is an essential number, and also an integer.




let person = "victor"
var loveStatement = "\(person) is "
switch person {
case "eva","natalie","siri" :
    loveStatement += "my wife, and also "
    fallthrough
default :
    loveStatement += "my best friend!"
}
print(loveStatement)// victor is my best friend!



let someString = "Some string literal value"
print(someString)

let myLover = "Victor"
print(myLover)

let myBestFriend = "zliang"
print(myBestFriend)


var emptyString = ""
if emptyString.isEmpty {
   print("String is empty")
}

var myString = String()
if myString.isEmpty {
    print("My String is Empty!")
}

var yourString = ""
if yourString == String() {
    print("Your String is Empty!")
}



var shoppingList = ["Bread", "Milk"]
print("The shopping list contains \(shoppingList.count) items.")



var shoppingList = ["Bread", "Milk"]
if shoppingList.isEmpty {
   print("The shopping list is empty.")
} else {
   print("The shopping list is not empty.")
}
// prints "The shopping list is not empty."


var shoppingList = ["Bread", "Milk"]
shoppingList.append("Flour")
print(shoppingList)



var shoppingList = ["Bread", "Milk"]
shoppingList[0] = "Two apples"
print(shoppingList)



var shoppingList = ["Syrup", "Bread", "Milk", "Apples"]
print("Before: \(shoppingList)")
shoppingList[1...3] = ["Bananas", "Oranges"]
print("After: \(shoppingList)")



var shoppingList = ["Bread", "Milk"]
print("Before: \(shoppingList)")
shoppingList.insert("Syrup", at: 0)
print("After: \(shoppingList)")


var myLunch = ["Soup", "Egg Bread", "Honey Tomato"]

print("I have \(myLunch) for lunch today.")

myLunch.insert("Noodles", at: 0)

print("Actually I have \(myLunch) for lunch today, and the last one is my favourite.")


var shoppingList = ["Syrup", "Milk", "Apples"]
let apples = shoppingList.removeLast()
print(apples)
print(shoppingList)


var allMyExBoyfriend = ["Sam", "Mike", "Jose", "Evan"]

let evan = allMyExBoyfriend.removeLast()

print(evan)
print(allMyExBoyfriend)




var shoppingList = ["Syrup", "Milk"]
print("Before: \(shoppingList)")
let syrup = shoppingList.remove(at:0)
print("After: \(shoppingList)")



var shoppingList = ["Bread", "Milk", "Syrup", "Apples"]
for item in shoppingList {
    print(item)
}





var shoppingList = ["Bread", "Milk", "Syrup", "Apples"]
for (index, value) in shoppingList.enumerated() {
    print("Item \(index + 1): \(value)")
}



var carList = ["Toyota", "Mazda", "Honda", "Ghblic", "Tesla"]
for (index, value) in carList.enumerated() {
    print("Item \(index + 1): \(value)")
}




var letters = Set<Character>()
print(letters)


var strings = Set<String>()
print(strings)

var studentName = Set<Use>()
print(studentName)




var names: Set<String> = ["David", "Susan", "Robert"]
print(names)


var books: Set<String> = ["Be an artist", "Stranger", "Yourselft"]
print(books)
    
    
    
var names: Set = ["David", "Susan", "Robert"]
print(names)

var numbers: Set = [1, 50, 3]
print(numbers)


