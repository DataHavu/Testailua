 Ohje: Pythonin "Hello World" -ohjelman luominen

## Mitä tulette tekemään
Tässä ohjeessa opit, kuinka kirjoittaa ja suorittaa yksinkertainen Python-ohjelma, joka tulostaa "Hello, World!" -viestin konsoliin. Tämä on klassinen ensimmäinen ohjelma, jonka useimmat ohjelmoijat kirjoittavat aloittaessaan uuden ohjelmointikielen opiskelun.

## Tarvittavat välineet
Ennen kuin aloitat, varmista, että sinulla on seuraavat työkalut ja ohjelmat asennettuna:

1. **Python** – Ohjelmointiympäristönä käytämme Pythonia. Asenna Python [täältä](https://www.python.org/downloads/) (valitse oikea versio käyttöjärjestelmäsi mukaan).
2. **Tekstieditori** – Voit käyttää mitä tahansa tekstieditoria, kuten Notepad++, Visual Studio Code tai vaikka Pythonin oma IDLE. Tärkeintä on, että voit kirjoittaa ja tallentaa tekstiä.

## Vaihe 1: Python-ohjelman kirjoittaminen

1. **Avaa tekstieditori** ja luo uusi tiedosto.
2. **Kirjoita seuraava koodi** tiedostoon:

    ```python
    print("Hello, World!")
    ```

3. **Tallenna tiedosto** nimellä `hello_world.py`. Huomaa, että tiedoston pääte täytyy olla `.py`, jotta Python tunnistaa sen ohjelmaksi.

## Vaihe 2: Ohjelman suorittaminen

### Windows:
1. Avaa **Komentorivi (Command Prompt)**. Voit tehdä tämän etsimällä "cmd" Käynnistä-valikosta.
2. Navigoi kansioon, johon tallensit `hello_world.py` -tiedoston. Käytä komentoa `cd` (Change Directory):

    ```
    cd C:\polku\kansioon
    ```

3. Suorita ohjelma kirjoittamalla:

    ```
    python hello_world.py
    ```

### MacOS / Linux:
1. Avaa **Terminal**.
2. Navigoi kansioon, jossa `hello_world.py` on tallennettu, käyttäen komentoa `cd`:

    ```
    cd /polku/kansioon
    ```

3. Suorita ohjelma kirjoittamalla:

    ```
    python3 hello_world.py
    ```

## Vaihe 3: Ohjelman tuloksen tarkastelu

Kun suoritat ohjelman, konsolissa pitäisi näkyä seuraava tulostus:

