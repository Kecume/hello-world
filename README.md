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
