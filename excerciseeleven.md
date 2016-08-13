#Regex

1. `/(?=.*[0-9]).(?=.*[!@#$%^&*]).*/`


#Test Strings

1. `ch@ngem3` -- pass

2. `ch@ng3m3` -- pass

3. `changeme`  -- does not pass

4. `ch@ngeme` -- does not pass

5. `chang3m3`  -- does not pass
