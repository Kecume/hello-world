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



var names: Set = ["David", "Susan", "Robert"]
print("Before: \(names)")
names.insert("Paul")
print("After: \(names)")


var numbers: Set = [1, 2, 3, 4, 5]
print("There have \(numbers.count) numbers. Ther are \(numbers).")
numbers.insert(20)
print("Now there have \(numbers.count) numbers. They are \(numbers).")




var names: Set = ["David", "Susan", "Robert"]
if names.contains("James") {
    print("James is here.")
} else {
    print("James is not with us.")
}


var magazines: Set = ["Milk", "Ceal", "IdN", "The Little Things"]
if magazines.contains("IdN") {
    print("I have one IdN magazine and it's my favorite.")
} else {
    print("I don't have any IdN here right now.")
}






var names: Set = ["David", "Susan", "Robert"]
for name in names {
   print("\(name)")
}


var colleagues: Set = ["Miya", "Lori", "Cayi" , "Jane", "Lee"]
for colleague in colleagues {
    print("\(colleague)")
}



var names: Set = ["David", "Susan", "Robert"]
for name in names.sorted() {
   print("\(name)")
}


var food: Set = ["Eggs", "Cakes", "Cherries", "Cauliflower"]
for food in food.sorted() {
    print("\(food)")
}





let oddDigits: Set = [1, 3, 5, 7, 9]
let evenDigits: Set = [0, 2, 4, 6, 8]

print("Set 1 contains \(oddDigits)")
print("Set 2 contains \(evenDigits)")
print("Union of the two sets will contain")
print(oddDigits.union(evenDigits).sorted())


let basketLeft: Set = ["Apple", "Pear", "Orange", "Watermelon"]
let basketRight: Set = ["Orange", "Grape", "Cherries"]

print("The left basket contains \(basketLeft)")
print("The right basket contains \(basketRight)")
print("Both baskets contains \(basketLeft.union(basketRight).sorted())")








let oddDigits: Set = [1, 3, 5, 7, 9]
let evenDigits: Set = [0, 2, 4, 6, 8]

print("Set 1 contains \(oddDigits)")
print("Set 2 contains \(evenDigits)")
print("Union of the two sets will contain")
print(oddDigits.union(evenDigits).sorted())

/*
Set 1 contains [5, 7, 3, 1, 9]
Set 2 contains [6, 2, 0, 4, 8]
Union of the two sets will contain
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
*/



var basketLeft: Set = ["Apple", "Pear", "Orange", "Watermelon", "Peach"]
var basketRight: Set = ["Orange", "Grape", "Cherries", "Apple"]

print("The left basket contains \(basketLeft.count) fruits. They are \(basketLeft.sorted())")

print("The right basket contains \(basketRight.count) fruits. They are \(basketRight.sorted()).")

print("There are \(basketLeft.union(basketRight).sorted()) in the baskets.")

print("Both baskets contains \(basketLeft.intersection(basketRight)), There have \(basketRight.symmetricDifference(basketLeft)) which the items the two baskets have not in commom.")

print("\(basketLeft.subtract(basketRight))")  // ??????????????????????????????????????

/*
Set 1 contains [5, 7, 3, 1, 9]
Set 2 contains [6, 2, 0, 4, 8]
Union of the two sets will contain
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
The left basket contains 5 fruits. They are ["Apple", "Orange", "Peach", "Pear", "Watermelon"]
The right basket contains 4 fruits. They are ["Apple", "Cherries", "Grape", "Orange"].
There are ["Apple", "Cherries", "Grape", "Orange", "Peach", "Pear", "Watermelon"] in the baskets.
Both baskets contains ["Orange", "Apple"], There have ["Pear", "Grape", "Cherries", "Watermelon", "Peach"] which the items the two baskets have not in commom.
()
*/

print("\(basketLeft.subtract(basketRight))")








let oddDigits: Set = [1, 3, 5, 7, 9]
let evenDigits: Set = [0, 2, 4, 6, 8]

print("Set 1 contains \(oddDigits)")
print("Set 2 contains \(evenDigits)")
print("Union of the two sets will contain")
print(oddDigits.union(evenDigits).sorted())


/*
Set 1 contains [5, 7, 3, 1, 9]
Set 2 contains [6, 2, 0, 4, 8]
Union of the two sets will contain
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
*/


let numGroupA: Set = [1, 20, 16, 3, 9, 41, 0]
let numGroupB: Set = [0, 1, 3, 6, 8, 21, 50]

print("Group 1 contains \(numGroupA)")
print("Group 2 contains \(numGroupB)")
print("Union of the two sets will contain.")
print(numGroupA.union(numGroupB).sorted())
print(numGroupA.symmetricDifference(numGroupB).sorted())
print("Group 1 and 2 both have \(numGroupA.intersection(numGroupB).sorted()).")

/*
Group 1 contains [16, 41, 20, 9, 3, 1, 0]
Group 2 contains [8, 21, 6, 50, 0, 1, 3]
Union of the two sets will contain
[0, 1, 3, 6, 8, 9, 16, 20, 21, 41, 50]
[6, 8, 9, 16, 20, 21, 41, 50]
Group 1 and 2 both have [0, 1, 3]
*/



var basketLeft: Set = ["Apple", "Pear", "Orange", "Watermelon", "Peach"]
var basketRight: Set = ["Orange", "Grape", "Cherries", "Apple"]

print("The left basket contains \(basketLeft.count) fruits. They are \(basketLeft.sorted())")

print("The right basket contains \(basketRight.count) fruits. They are \(basketRight.sorted()).")

print("There are \(basketLeft.union(basketRight).sorted()) in the baskets.")

print("Both baskets contains \(basketLeft.intersection(basketRight)), There have \(basketRight.symmetricDifference(basketLeft)) which the items the two baskets have not in commom.")

print(basketLeft.union(basketRight))

print("\(basketRight.subtract(basketLeft))")  // ??????????????????????????????????????

/*
Set 1 contains [5, 7, 3, 1, 9]
Set 2 contains [6, 2, 0, 4, 8]
Union of the two sets will contain
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
The left basket contains 5 fruits. They are ["Apple", "Orange", "Peach", "Pear", "Watermelon"]
The right basket contains 4 fruits. They are ["Apple", "Cherries", "Grape", "Orange"].
There are ["Apple", "Cherries", "Grape", "Orange", "Peach", "Pear", "Watermelon"] in the baskets.
Both baskets contains ["Orange", "Apple"], There have ["Pear", "Grape", "Cherries", "Watermelon", "Peach"] which the items the two baskets have not in commom.
()
*/

var threeDoubles = [Double] (repeating: 3, count: 4)
var anotherThreeDoubles = [Double] (repeating: 2.5, count: 3)
var sixDoubles = threeDoubles + anotherThreeDoubles
print(sixDoubles)

/*
Group 1 contains [16, 41, 20, 9, 3, 1, 0]
Group 2 contains [8, 21, 6, 50, 0, 1, 3]
Union of the two sets will contain
[0, 1, 3, 6, 8, 9, 16, 20, 21, 41, 50]
[6, 8, 9, 16, 20, 21, 41, 50]
Group 1 and 2 both have [0, 1, 3]
*/


















