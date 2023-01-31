# GitWorkshop
Opastus Gitin käyttöön

 1. Luo GitHub tili
 2. Lataa ja asenna Git. Asennuspaketit ovat saatavilla useille eri alustoille, kuten Windows, Mac ja Linux. Voit ladata asennuspaketin osoitteesta         https://git-scm.com/downloads
 3. Konfiguroi Git: Asenna Git ja konfiguroi se käyttäjänimelläsi ja sähköpostiosoitteellasi. Tämä tieto liitetään jokaiseen commitiin.
    Käytä seuraavia komentoja konfiguroidaksesi käyttäjänimesi ja sähköpostiosoitteesi:
    
       `git config --global user.name "Your Name"`
       
       `git config --global user.email "your.email@example.com"`
 
 4. (Valinnainen) Määritä oletuseditori. 
    Git käyttää oletuksena komentorivieditoria, mutta voit määrittää eri editorin käyttöön komennolla:
    
    `git config --global core.editor "nano"`
    
 5. Tarkista asennus ja konfigurointi käyttämällä komentoa:
   
    `git --version`
    
    Tämä tulostaa gitin version joka kertoo että asennus on onnistunut.
 

  6. Git Hubissa:
  
    - Klikkaa "New repository" -painiketta
    - Anna repositoriolle nimi ja mahdollinen kuvaus
    - Valitse julkinen tai yksityinen
    - Valitse haluamasi repositoryn luontityyppi (esim. "python")
    - Klikkaa "Create repository" -painiketta
    
  7. Lokaalisti:
  
    - Avaa terminaali
    - Mene haluamallesi hakemistolle
    - Käytä komentoa "git init [repositoryn nimi]"
    - Lisää haluamasi tiedostot komennolla "git add [tiedoston nimi]"
    - Tee ensimmäinen commit komennolla "git commit -m '[viesti]'"
    - Lisää GitHub-repositorio remote-lähteeksi komennolla "git remote add origin git@github.com:[käyttäjänimi]/[repositoryn nimi].git"
    - Pushaa tiedostot GitHubiin komennolla "git push -u origin master".

   # Git-komentoja
   
Seuraavassa on joitain peruskomentoja, joita voit käyttää Git-komentorivillä:

1. **`git init`**: Tämä komento luo uuden versionhallintaprojektin kansioon, jossa se suoritetaan.
2. **`git status`**: Tämä komento näyttää tiedostot, jotka ovat muuttuneet ja tiedostot, jotka ovat valmiina tallennettaviksi (commit)
3. **`git add`**: Tämä komento lisää tiedoston tai kansion versionhallintaan. Voit käyttää **`git add .`** lisätäksesi kaikki kansion tiedostot versionhallintaan.
4. **`git commit`**: Tämä komento tallentaa muutokset versionhallintaan. Seuraava komento **`git commit -m "message"`** tallentaa muutokset ja lisää viestin joka kertoo mitä muutoksia on tehty.
5. **`git log`**: Tämä komento näyttää lokin kaikista aiemmista tallennuksista (commit)
6. **`git diff`**: Tämä komento näyttää erot nykyiseen ja edelliseen version välillä.
7. **`git branch`**: Tämä komento näyttää kaikki projektin haarat (branch) ja näyttää mihin haaraan ollaan tällä hetkellä.
8. **`git checkout`**: Tämä komento vaihtaa haaraa tai palauttaa tiedoston edelliseen versioon.
  
  Lisää komentoja löydät täältä: https://git-scm.com/docs
 
 
 
 
 
 
 
 
 
 
 
   
   
   
   
   
