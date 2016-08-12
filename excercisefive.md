#Regex
1. `/(?<month>|[0][1-9]|[1][0-2])\/(?<date>[0-2][1-9]|[3][0-1])\/(?<year>\w{4})/`


#Test Strings
1. `12/31/3000`  -- pass

2. `02/22/1996`  -- pass

3. `13/32/3333`  -- does not pass

4. `00/00/0000`  -- does not pass
