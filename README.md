# Tehtävälista




### 1) Hahmotellaan pelin osa-alueet
- Mitä objekteja peli sisältää
- Mitkä ovat pelin sisältämien objektien väliset suhteet
- Mikä on pelin tavoite ja miten se saavutetaan
- Tähän voi listata pienempiä haasteita matkalle

### 2) Sääntökirjaa

- 9x9 kenttä
- 2 Pelaajaa
- 3-7 Valittavaa classia
- Yhtäaikaiset vuorot, joissa molemmat pelaajat päättävät:
- Creatureiden liikkeet
- Spellien castaamisesta
- Uusien creatureiden spawnaamisesta

### 3) Pelin mekaniikat:

##### a) Classit:

Jokaisella tietty määrä Slot:eja spelleille,creatureille, passiivisille kyvyille. Ideana taiteilu niukkuuden kanssa.

- Creaturet
- spellit
- Passiiviset kyvyt

##### b) Creaturet:

- Attack
- Health
- Speed
- "Ability Points"
- Score Value
- Erilaisia passiivisia/Aktivoitavia kykyjä


##### c) Spellit

- Efekti
- Resurssimaksu
- CastTime
- Vaikutusalue
- Rajattu tieto vastustajalle

### 4) Vuoron rakenne

- "Upkeep"
- Molemmat pelaajat päättävät liikkeistään
- Asiat tapahtuvat Step:ien perustella
- Scoreboard päivittyy hallinnan perusteella


### 5) Graafinen ilme / Musiikki

- Jukalla on piirtopöytä ja kaksi kättä
- Rocksmith voi taipua .rec musiikin nauhoittamiseen

