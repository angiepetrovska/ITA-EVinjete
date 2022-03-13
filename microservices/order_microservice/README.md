# Order - naročanje e-vinjete

## Opis storitve
Uporabnik bo lahko naročil e-vinjeto za svoje vozilo. 

Zahtevane podatke:
- e-mail
- registerska številka vozila
- datum začetka veljavnosti vinjete

Po uspešnem vnosu podatkov, se podatki zapišejo v MongoDB.

## DDD digram
![DDD_Order](https://user-images.githubusercontent.com/44358450/158067578-e197df3f-8a15-4e9e-b432-c8f391eb6264.png)

## Funkcinalne in nefunkcionalne zahteve
Funkcionalne | Nefunkcionalne
------------ | -------------
Vpisovanje podatkov | Validacija podatkov v majn kot 10s
Izbira tipa e-vinjete | Izbira e-vinjete glede na cestninski razred in trajanje vinjete
Status izvedbe naročila | Naročilo se izvede v majn kot 30s
