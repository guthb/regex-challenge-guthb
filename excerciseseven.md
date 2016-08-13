#Regex

1.`/List\<int\>\s(?<enteredValue>\S+)\s\=\snew\sList\<int\>\(\)\;/`



#Test Strings
1. ` List<int> FrankList = new List<int>();` -- pass
2. ` List<int> my_List = new List<int>(); ` -- pass
3. ` List<double> my_List = new List<double>(); ` -- does not pass
