#Regex

1. `/\S*@(?<domainname>\w+).(?<topleveldomain>com|org|net|io|ly)/`


#Test Strings
1. `yourname@yourdomain.com` -- pass
2.  `yourname@yourdomain.org` -- pass
3.  `yourname@yourdomain.net` -- pass
4.  `yourname@yourdomain.io` -- pass
5.  `yourname@yourdomain.ly` -- pass
6.  `yourname@yourdomain.biz`  -- does not pass
7.  `yourname@yourdomain.com.uk` -- does not pass
