
# AM2R-cat

![AM2R-cat](./AM2Rcat.png)

Traducció al català d'**AM2R - El Retron de Samus**.

> **Nota:** Necessites una còpia d'AM2R per aplicar aquesta traducció.

## Requisits

- **AM2R 1.1** (necessària per aplicar el pegat correctament amb l'AM2R Launcher).
- **AM2R Launcher** per gestionar i aplicar pegats i actualitzacions de la comunitat.
  - Més informació i instruccions: https://github.com/AM2R-Community-Developers/AM2RLauncher

## Instal·lació manual (idioma)

1. Baixa els fitxers `catalan.ini` i `languages.txt` d'aquest repositori.
2. Copia'ls a la carpeta `AM2R/lang` del joc.
3. Si ja tens un `languages.txt`, assegura't que inclogui una línia amb:
   ```
   catalan.ini
   ```
4. Engega el joc i selecciona **Català** al menú d'opcions d'idioma.

## AM2R Launcher / actualitzacions de la comunitat

### Windows / Android (AM2R Launcher)

Si utilitzes el perfil **Community Updates (Latest)**, col·loca els fitxers `languages.txt` i `catalan.ini` a:

```
AM2R/AM2RLauncher/Profiles/Community Updates (Latest)/lang
```

### Mac (AM2R-Autopatcher-Mac)

Si utilitzes **AM2R-Autopatcher-Mac** amb el perfil **Community Updates**, copia els fitxers a:

```
AM2R-Autopatcher-Mac/data/files_to_copy/lang
```

Un cop els arxius siguin al lloc correcte, torna a executar l'script del patcher per tenir l'idioma disponible.

> **Nota (Mac):** els gràfics del títol en català no estan disponibles per aquesta versió.

## Títol personalitzat en català (opcional)

### Instal·lació manual

1. A la carpeta del joc, crea `titles` dins de `AM2R/lang/` (si no existeix).
2. Copia-hi el PNG del títol personalitzat (per exemple, el que trobaràs a `titles/` d'aquest repositori).
3. Engega el joc: amb la traducció catalana activa, el joc utilitzarà la imatge de títol de:
   ```
   AM2R/lang/titles/
   ```

### AM2R Launcher (títol personalitzat)

Si utilitzes el perfil **Community Updates (Latest)**, crea també la carpeta i col·loca el PNG a:

```
AM2R/AM2RLauncher/Profiles/Community Updates (Latest)/lang/titles/
```

## Referències

- AM2R Launcher (perfils, pegats i instruccions detallades): https://github.com/AM2R-Community-Developers/AM2RLauncher
