#Regex

1. `/((http|https)://)(?!msdn)(\S+)/`


#Test Strings
1. `https://regex101.com` -- pass
2. `http://facebook.com` -- pass
3. `https://www.godaddy.com` -- pass
4. `https://msdn.microsoft.com` -- ignores
