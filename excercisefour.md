#Regex

1.`/(Mon|Tue|Wed|Thu|Fri|Sat|Sun)\s(Jan|Feb|Mar|May|Jun|Jul|Aug|Sep|Oct|Nov|Dec)\s+([0-2][0-9]\,\s(\w+)|([3][0-1]))`


#Test Strings
1. `Wed Aug 11, 2013` --  passes
2. `Mon Sept 15, 8080` -- passes
3. `Sat Oct 32, 2000`  -- does not pass
