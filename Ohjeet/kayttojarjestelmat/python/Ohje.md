---
id: 4528
kategoriat:
- kayttojarjestelmat
- python
tags: null
title: Virtuaaliympäristön käyttöönotto Pythonissa
---

Tässä ohjeessa kerromme, kuinka voit luoda ja käyttää virtuaaliympäristöä (`venv`) Python-projekteissasi Windows 10:llä.
eif
## Vaatimukset:
- Windows 10
- Python 3.6 tai uudempi asennettuna

## Virtuaaliympäristön luominen
Avaa komentokehote (Command Prompt) ja siirry projektikansioon:

```sh
cd C:\polku\projektiin
```

Luo uusi virtuaaliympäristö komennolla:

```sh
python -m venv venv
```

## Virtuaaliympäristön aktivointi
Aktivoi ympäristö seuraavasti:

```sh
venv\Scripts\activate
```

Tämän jälkeen komentokehotteessa pitäisi näkyä `(venv)`, mikä tarkoittaa, että virtuaaliympäristö on aktiivinen.

## Virtuaaliympäristön poistaminen käytöstä
Jos haluat poistua virtuaaliympäristöstä, käytä komentoa:

```sh
deactivate
```

## Usein kysytyt kysymykset
<details>
  <summary>Miksi käyttää virtuaaliympäristöä?</summary>
  Virtuaaliympäristö auttaa pitämään riippuvuudet erillään eri projekteille, jolloin ne eivät aiheuta konflikteja.
</details>

<details>
  <summary>Windows 10</summary>
  Käyttöjärjestelmä.
</details>