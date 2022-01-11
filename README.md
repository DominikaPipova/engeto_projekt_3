 TO BE DELETED - [Learn more about READMEs](https://help.github.com/en/articles/about-readmes)

# Engeto projekt 3

Třetí projekt na Python Akademii od Engeta.

## Popis projektu

Tento projekt slouží k extrahování výsledků z parlamentních voleb v roce 2017. Odkaz k prohlédnutí najdete [zde](https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ).

## Instalace knihoven

Knihovny, které jsou použity v kódu jsou uložené v souboru `requirements.txt` . Pro instalaci doporučuji použít nové virtální prostředí a s nainstalovaným manažerem spustit následovně:

`$ pip3 --version                     # overim verzi manazeru`

`$ pip3 install - r requirements.txt  # nainstalujeme knihovny`



## Spuštění projektu

Spuštění souboru `election-scraper.py` v rámci přík. řádku požaduje dva povinné argumenty.

`python election-scraper <odkaz-uzemniho-celku> <vysledny-soubor>`
  
Následně se vám stáhnou výsledky jako soubor s příponou `.csv`.
  
## Ukázka projektu
  
Výsledky hlasování pro okres Prostějov:

  1. argument: `https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103`
  2. argument: `vysledky_prostejov.csv`
  
Spuštění programu:
 `python election-scraper.py 'https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103' 'vysledky_prostejov.csv'` 
  
Průběh stahování:
 `STAHUJI DATA Z VYBRANEHO URL: https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103
  UKLADAM DO SOUBORU: vysledky_prostejov.csv
  UKONCUJI election-scraper
  `
  
Částečný výstup:
  
`code, location, registered, envelopes, valid, ...
DODELAT
...
`
