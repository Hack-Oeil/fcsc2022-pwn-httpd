# FCSC 2022 httpd

On vous demande d'auditer ce serveur web sandboxé.


Fichiers :
- [httpd](httpd)
- [ld-2.33.so](ld-2.33.so)
- [libc-2.33.so](libc-2.33.so)
- [httpd.src.tar.gz](httpd.src.tar.gz)


Auteurs : XeR

Origine : [httpd](https://hackropole.fr/fr/challenges/pwn/fcsc2022-pwn-httpd/)

-----------


## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc httpd.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-pwn-httpd.git

> cd fcsc2022-pwn-httpd


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2022-pwn-httpd/