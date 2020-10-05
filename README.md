# GitWorkshop
Opastus Gitin käyttöön

1. Luo GitHub tili
2. Asenna git koneelle: https://git-scm.com/downloads
3. Luo GitHubissa repository, eli uusi repo.

   - anna sille kuvaava nimi
   - kuvaus, mitä käsittelee (ei pakollinen)
   - julkinen, kaikki pääsevät
4. Terminal 

-> git clone <url>
5. Valitse kansio terminaalissa
   
   - ls -> antaa listan kansioista -> näkyy uusi kansio
   - cd -> siirry kansioon (uuteen repoon)
6. Luo terminaalista käsin uusi kansio

   - touch hello.html
   - ls -> uusi kansio näkyy
7. Luo HTML runko tai muuta sisältöä uuteen kansioon
8. Terminaalissa
   
   -> git add <kansion nimi>
   - lisää yhden tietyn kansion GitHubiin

   -> git commit -m "viesti"
   - viestiin lisätään kuvaus siitä, mitä muutoksia teit
   
   -> git status
   - mitä sanoo?
   
   -> git push
   - vie muutokset GitHubiin
9. Avaa hello.html
10. Tee uusia muutoksia hello.html kansioon
11. Vie kaikki uudet muutokset GitHubiin

   -> git commit -am "viesti"
   -> git status 
   -> git push

Kuvitellaan, että joku muukin on mukana samassa projektissa ja haluat saada päivitetyn koodin omalle koneelle.

12. Tee muutoksia kansioon GitHubissa

   -> commit viesti muutokseen, mitä teit
13. Omassa terminaalissa

   -> git pull
   - saadaan "jonkun muun" tekemät muutokset omalle koneelle
   
   
   
   
   
   
   
   
   
