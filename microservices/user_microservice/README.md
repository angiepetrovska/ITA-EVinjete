# User - prijava na e-vinjete

## Opis storitve
Uporabnik se lahko prijavi v sistem in pridobi link za nadaljevanje z nakupom

Zahtevane podatke:
- e-mail

Po uspešnem vnosu podatkov, se podatki zapišejo v MongoDB.

## DDD digram
![DDL_User](https://user-images.githubusercontent.com/44358450/158067715-b2952ca9-692b-4778-a32a-19d1077b0ec4.png)

## Funkcinalne in nefunkcionalne zahteve
Funkcionalne | Nefunkcionalne
------------ | -------------
Obdelava zahteva za prijavo | Da se pripravi povratni email v 30s
Seja uporanika | Seja poteče v 1uri
Preverjanje kupljenih vinjet | V primeru, da uporabnik ima že kupljeno vinjeto se izpiše opozorilo

