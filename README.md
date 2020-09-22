<div align="center">

## Complete String Manipulation


</div>

### Description

It's a part of my program title complete vb.net functions that include all vb.net functions, financial, file i/o, math etc., This Tutorial help you a lot to format convert string..,
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Dennis M\. Santiago](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/dennis-m-santiago.md)
**Level**          |Beginner
**User Rating**    |4.2 (38 globes from 9 users)
**Compatibility**  |VB\.NET, C\+\+\.NET
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__10-26.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/dennis-m-santiago-complete-string-manipulation__10-4509/archive/master.zip)





### Source Code

```
Complete String Manipulation
Asc(), AscW(), Chr(), ChrW(), Filter(),
InStr(), InStrRev(), Join(), LCase(),
Left(), Len(), LTrim(), Mid(), Mid,
Replace(), Right(), RTrim(), Space(),
Split(), StrComp(), StrConv(), StrDup(), StrReverse(), Trim(), UCase()
-------------------------------------------------
Asc(character), AscW(string)
The Asc() function returns the character
code corresponding to the character argument
The AscW() function returns the Unicode character
code except on platforms that do not support
Unicode.
ex. Output = Asc(W)(MysingleString) MysingleString = w output =119
_________________________________________________
Chr(Value as Integer)
The Chr() function is the inverse of the Asc() function and returns the character associated
with the specified character code. Use this function to print characters that don’t appear
on the keyboard (such as line feeds or special symbols).
The ChrW() function returns a string containing the Unicode character except on platforms that don’t support Unicode, in which case, the behavior is identical to that of the Chr() function.
ex. Output = Chr(W)(MySingleString) MysingleString = 119 output =w
_________________________________________________
Filter(inputStrings, value[, include][, compare])
This function returns an array containing part of a string array
ex.
    Dim intRecCnt As Integer
    Dim intCntr As Integer
    Dim selNames() As String
    Dim Names() As String _ = "Dennis", "Manjon", "Santiago"}
 'Create the Filtered array from the Full array
    selNames = Filter(Names, MyInputString)
 'Determine the number of elements in the array
    intRecCnt = UBound(selNames)
 'Add Elements to ListBox for each element
 'in the array
    For intCntr = 0 To intRecCnt
     LBOutput.Items.Add(selNames(intCntr))
    Next intCntr
MyInputString ="Dennis"
the Output get the Location = 1
________________________________________________
InStr([startPos,] string1, string2[, compare])
InStrRev(string1, string2[, start][, compare]) #
InStr(InputString1, _ InputString2,CompareMethod.Text)
I choice CompareMethod.Text, if the the Input string is equal then it return 1 else 0
__________________________________________________
Join(list[, delimiter])
Dim ArrayList() As String = {"Dennis", "Santiago"}
txtOutPut.Text = "The output is : " & Join(ArrayList, MyJoinString)
MyJoinString " Manjon " Output Dennis manjon Santiago
__________________________________________________
LCase(String) convert to lowercase
ex. lCase(D) output = d
__________________________________________________
Left(string, Length)
Output = Left("Dennis",2) = "De"
__________________________________________________
len(String)
len(Dennis)
 Output =6
_________________________________________________
LTrim(string) LTrim() RemoveSpace from left until not found Character
 output = L Trim(" Dennis ")
Result= "Dennis "
__________________________________________________
Mid(string, start, [length])
Str = Mid("Dennis",2 ,"3")
Output = enn
_________________________________________________
Replace(expression, find, replacewith[, start][, count][, compare])
Replace("Dennis Santiago", "Dennis", "Den")
Output = Den Santiago
_________________________________________________
Right(String,Length)
Output = Right("Dennis",3)
output =nis
_________________________________________________
RTrim(string) Remove space from the rightside
Output = Rtrim("Dennis  ")
output="Dennis"
__________________________________________________
Space(number)
Space(3)
make 3 space
_________________________________________________
Split(expression[, delimiter][, count][, compare])
 This function is the counterpart of the Join() function. It returns a one-dimensional array containing a number of substrings.
Split("Dennis Santiago","Den" , 2)
Output = Nis Santiago
__________________________________________________
StrComp(string1, string2[, compare])
Value  Description
–1   string1 is less than string2.
 0   string1 is equal to string2.
 1   string1 is greater than string2.
StrComp("Dennis", "Santiago")
output = -1
_________________________________________________
StrConv(string, conversion)
enter a Number on Conversion 1 to 9 For String Format
StrConv("Dennis", 1)
Output = DENNIS
__________________________________________________
StrDup(number, character)
This function returns a string of number
characters, all of which are character
StrDup(3, "d")
Output = DDD
_________________________________________________
StrReverse(string)
output = StrReverse("Dennis")
Output =sinneD
_________________________________________________
Trim(String)
Remove all Space on String both left and right
Output = Trim(" Dennis ")
output = "Dennis"
_________________________________________________
UCase(string)
Convert to uppercase
Output =UCase("Dennis")
Output = DENNIS
_________________________________________________
By: Dennis M. Santiago :Email Add Explicitmaker@yahoo.com--- don't forget to VOTE for me |-:) Thanks
```

