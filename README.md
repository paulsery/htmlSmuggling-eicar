# htmlSmuggling eicar
PoC by Sofiane Hamlaoui (offensive-security/defense-evasion/file-smuggling-with-html-and-javascript.md)


wget -o eicar.com https://www.eicar.org/download/eicar-com/?wpdmdl=8840&refresh=65abf9b7391a61705769399
cat eicar.com  | base64 -w 100  
    output: WDVPIVAlQEFQWzRcUFpYNTQoUF4pN0NDKTd9JEVJQ0FSLVNUQU5EQVJELUFOVElWSVJVUy1URVNULUZJTEUhJEgrSCo=
    creates base64 encoding to create the download file (the -w 100 is an arbitrary number to keep output to one line)
