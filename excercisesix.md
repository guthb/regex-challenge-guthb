#Regex

1.`/function\s(\w+)\(\)\s\{return\s(?<returnValue>\S+)\;\}/`



#Test Strings
1. ` function returnOne() {return 1;}` -- pass
2. ` function returnFive() {return 5;}` -- pass
3. ` smell returnOne() {return z;} ` -- does not pass
