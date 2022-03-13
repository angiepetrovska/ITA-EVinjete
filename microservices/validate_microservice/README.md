# Validate - validacija registerske številke vozila

## Opis storitve
Pridobljena registerske številka, se preveri ali obstaja v bazi plačano e-vinjeto

Zahtevane podatke:
- registracijska številka

## DDD digram
![DDL_Validate](https://user-images.githubusercontent.com/44358450/158067760-56f29f55-a71b-44aa-afe4-9d91307cc5ac.png)


## Funkcinalne in nefunkcionalne zahteve
Funkcionalne | Nefunkcionalne
------------ | -------------
Preverjanje registrerske številke | Preverjanje se izvede v 60s
Priprava sporočila | Priprava sporočila za opomin neobstajanje/neveljavnost registerske številke v 60s
Pošiljanje sporočila | Sporočila se pošljejo v 60s
