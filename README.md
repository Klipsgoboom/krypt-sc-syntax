Krypt-Sc Browser:
**Change krypt web image support to match the rest

The first line of your website must be kryptsc
The last line of your website must be |

h - h'this is how you make a heading'
p - p'this is how you make a paragraph'
title - title 'This text is a title'
img - img (image) (make sure to use an IMAGE not a Decal)
hyperlink(displaytext, url)
copybox(text) - a box that you can copy text from
align - (0=left, 1=center, 2 = right)
colorFromHex(hex) - set color of text and stuff

C++, Lua, JS distributions:

rgb(0-255,0-255,0-255)

img(link, x, y, width, height)

coordx(number)
coordy(number)

settext(string)

save(dataName, var1) *requires additional module
load(dataName, var1) *requires additional module
deletefile(dataName) = deletes specified file
deleteall = deletes all saved data

sprite(x,y,width,height)

function(name, actions)

skip() -useful instead of goto if only jumping one line

callfunction(name)

if(var1, arg, var2, output1, output2) >, <, ==, != (doesnt require })

goto(arg)

exit() exits current function

screen(x, y)

sign = use already set colors and text to create a sign

bt1click(functionName)
bt2click(functionName)


loop = anything after this will constantly run/be checked ex: button presses and their results

clr = clears screen

var(var1, operator, var2, var3) (+, -, *, /, .. are the operators) (.. is like lua, combines two args as strings
//var (1,2,3,4)

.int = make following data into int ex: settext.int 10 (10 will be registered as an integer) 
.var = get the value of the variable ex: settext.var 1 (sets text to the variable 1's value)
.val = make the following data a number ex: settext.val 1.5 (1.5 will be registered as a number)
.str = make the following data a string ex: settext.str 153 (153 will be registered as a string)


checkvarresult(var1, action1, action2, action3, action4, action5)

setvar(var num, value)

part(useVariable(true, false),name, property value, ) (Roblox Lua Only) 
partRead(name, property, output var)

YOU MUST DO (x, y)
arg1, SPACE arg2 




Deprecated elements

coordxvar(var) - deprecated (already removed in lua)
coordyvar(var) - deprecated (already removed in lua)
settextvar(var) - deprecated

bt1click(action1, action2, action3, action4, 5, 6) = checks for a click on btn 1 and runs following instructions
bt2click(action1, action2, action3, action4, 5, 6) = checks for a click on btn 1 and runs following instructions

backr = set background color red
backg = set background color green
backb = set background color blue

frontr = set color red
frontg = set color green
frontb = set color blue

