```
┌──(kali㉿yurs)-[/]
└─$ feroxbuster -u http://URL -k -H "User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:121.0) Gecko/20100101 Firefox/121.0" --rate-limit 300 -L 1 -w bitrix_fuzz.txt -C 404 -H 'Cookie: BITRIX_SM_LOGIN=ivan...; PHPSESSID=DjuVEr....; BITRIX_SM_SOUND_LOGIN_PLAYED=Y'
```

OR

```
┌──(kali㉿yurs)-[/]
└─$ feroxbuster -u http://URL -k -H "User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:121.0) Gecko/20100101 Firefox/121.0" --rate-limit 300 -L 1 -w bitrix_fuzz.txt -C 404
```
