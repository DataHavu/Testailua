---
id: 4561
julkaistu: false
kategoriat:
  - kayttojarjestelmat
  - python
tags:
  - aloittelija
title: Python tulostus
featured_media:
---

## Johdanto

  

Tässä ohjeessa opit, kuinka luot Python-ohjelmassa `main`-funktion ja tulostat tekstin "Moikka Maailma!". `main`-funktion käyttäminen on hyvä tapa järjestää koodi selkeäksi ja helposti luettavaksi.!


---

  

## Esivaatimukset

  

Ennen kuin aloitat, varmista, että sinulla on seuraavat asiat valmiina:

> Testi quote

TESTAILUA
> [!DANGER]
> **VAARA!** Tämä on vakava varoitus.

- Pythonin asennettuna tietokoneellesi (versio 3.x suositeltava)

- Tekstieditori, kuten VS Code, PyCharm tai vaikka Muistio

- Perustiedot Python-ohjelmoinnista (esim. tulostuskomennon `print` käyttäminen)

  

---

  

## Vaiheittaiset ohjeet

  

### **Vaihe 1: Luo Python-tiedosto**

  

Luo uusi tiedosto nimeltä `main.py`.

  

```bash

# Luo uusi tiedosto komentorivillä (Linux/macOS):

touch main.py

  

# Windowsissa voit luoda tiedoston esimerkiksi Notepadilla tai VS Codella.

```

  

**Odottava tulos:**

  

Tiedosto `main.py` ilmestyy valitsemaasi kansioon.

  

### **Vaihe 2: Kirjoita `main`-funktio**

  

Avaa `main.py` ja kirjoita seuraava koodi:

  

```python

# Määritellään funktio nimeltä main

def main():

    print("Moikka Maailma!")

  

# Tarkistetaan, onko tiedosto ajettu suoraan

if __name__ == "__main__":

    main()

```

  

#### **Mikä on funktio?**

Funktio on koodilohko, joka suorittaa tietyn tehtävän.

Se määritellään Pythonissa `def`-avainsanalla.

Tässä tapauksessa `main`-funktio sisältää vain yhden komennon, `print()`.

  

#### **Mikä on `print()`?**

`print()` on Pythonin sisäänrakennettu funktio, joka tulostaa tekstin tai muun arvon näytölle. Tässä tapauksessa se tulostaa tekstin "Moikka Maailma!".

  

#### **Miksi käytetään `if __name__ == "__main__"`?**

Tämä tarkistaa, onko tiedosto ajettu suoraan vai tuotu moduulina toiseen ohjelmaan.

- Jos tiedosto suoritetaan suoraan, `__name__`-muuttuja saa arvon "__main__" ja `main()` suoritetaan.

- Jos tiedosto tuodaan moduulina toiseen ohjelmaan, `main()` ei suoriteta automaattisesti.

  

**Odottava tulos:**

  

Kun suoritat ohjelman, näet seuraavan tulosteen:

  

```bash

Moikka Maailma!

```

  

---

  

## Vianmääritys

  

<details>
  <summary>Ongelma 1: `SyntaxError: invalid syntax`</summary>
  **Syy.** Koodissa voi olla kirjoitusvirhe, väärin asetettu sulkumerkki, tai käytät vanhaa Python-versiota (Python 2.x).
  
  **Ratkaisu:** Tarkista, että koodi on oikein kirjoitettu, että sulut ovat oikein ja käytä Python 3.x -versiota.
</details>

<details>
  <summary>Ongelma 2: `NameError: name 'main' is not defined`</summary>
  **Syy:** Funktiota `main` ei ole määritelty tai se ei ole oikein määritelty ennen kutsumista.
  
  **Ratkaisu:** Varmista, että `main`-funktio on määritelty ja että se on kutsuttu oikeassa järjestyksessä ohjelman alussa.
</details>


  

---

  

## UKK (Usein kysytyt kysymykset)

  <details> 
	  <summary>Miksi käytetään `if __name__ == "__main__"` -rakennetta?</summary>
	   Se varmistaa, että koodi suoritetaan vain, jos tiedosto ajetaan suoraan, eikä silloin kun se tuodaan moduulina toiseen ohjelmaan. 
   </details> 
   
   <details>
    <summary>Voiko `main`-funktion nimen muuttaa?</summary>
     Kyllä, voit antaa sille minkä tahansa nimen, mutta `main` on yleisesti käytetty standardi. </details>

  

---

  

## Yhteenveto

  

Tässä ohjeessa opit:

  

- Luomaan Python-ohjelman, joka käyttää `main`-funktiota

- Tulostamaan tekstin "Moikka Maailma!"

- Ymmärtämään `if __name__ == "__main__"` -rakenteen merkityksen

  

---

  

## Lisäresurssit

  

- [Pythonin virallinen dokumentaatio](https://docs.python.org/3/)

- [Python-opas aloittelijoille](https://realpython.com/python-beginners-guide/)
