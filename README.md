# h0-alku

Tämä on alkutehävä [Tero Karvisen](https://terokarvinen.com/tunkeutumistestaus-ict4tn027-3010-syksylla-2022/#h0-alkutehtava) Tunkeutumistestaus kursille

## analysoi verkkoliikennettä 

Aloin asentamalla wireshark ohjelman tietokoneelleni. 
Asennuksen jälkeen, aloitin oman verkon liikenteen kuuntelun.

![image](https://user-images.githubusercontent.com/93308960/197474161-70dace7e-1e15-47ac-a887-38423bd70a92.png)

Aloitin tämän painamalla kuvassa korostetusta kohdasta.

![image](https://user-images.githubusercontent.com/93308960/197472215-cfe6ac80-6299-48d6-b1e2-f75bf74e4ce3.png)

Tietyn ajan jälkeen lopetin verkonskannaamisen. 

Rupesin analysoimaan saamania tuloksia

 * ensin nähdään sakannauksen numerot 1, 2  & 3
 * seuraavaksi on aika eli milloin skannaus on tehty päivämäärä 2022-10-24 ja kellon aika 10.47
 * ajan jälkeen lähde eli IP-osoite ja broadcast
 * sitten tulee tietoliikenneprotokolla eli tässä tapauksessa UDP & ARP
 * protokollan jälkeen tulee pituus
 * Lopuksi tulee muuta infoa, tässä tapauksessa kahdessa ensimmäisessä kohdassa näkyy UDP payload pituus. Alimmassa näkyy ARP kysely.

![image](https://user-images.githubusercontent.com/93308960/197474494-6ecec966-8213-4037-ae62-10f8c38c8e56.png)

Tuloksena tuli ARP kysely ja UDP pituus.


