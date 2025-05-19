# Skyblock 

### ⏳Time? How much for a season?
| Durata     | Competitività               | Note                                                                 |
|------------|-----------------------------|----------------------------------------------------------------------|
| **2 mesi** | Estremamente competitiva    | Non attiri giocatori casual.                                        |
| **4 mesi** | Moderatamente competitiva   | Uno che entra a 2 mesi può comunque giocare in modo tranquillo.     |
| **6 mesi** | Troppo lunga                | Attiri player casual, che poi si legano alle isole e ci rimangono male al reset. |
| **1 anno+**| Insostenibile               | Fai la fine di War (Con nessun player online).. |

Preferisco l’opzione da **4 mesi**: offre un buon equilibrio tra competizione e possibilità di giocare anche in modo più rilassato senza bruciarsi in fretta.

---
### 📊 Sistema di Progressione ELO – Skyblock Competitiva

#### 🧮 Formula di Calcolo
L'incremento dell'ELO per ogni 100 punti guadagnati è definito dalla seguente formula:
$$
\Delta ELO = \frac{100}{\left(  \frac{x +  1000}{2000}  \right)^{1.5}}
$$

Dove:
-  $x$ è l’ELO attuale del giocatore.
- La funzione assicura crescita fluida e bilanciata.
- Il termine $+1000$ evita che a ELO bassi il guadagno esploda.

#### 🏆 Punti Totali Richiesti per Raggiungere un ELO

| ELO Attuale | Rank              | Incremento per 100 punti | Punti richiesti da 0 |
|-------------|-------------------|---------------------------|------------------------|
| 0           | Novizio I         | 282.8                     | 0                      |
| 200         | Novizio II        | 215.2                     | 80                     |
| 400         | Apprendista I     | 170.7                     | 190                    |
| 600         | Apprendista II    | 139.8                     | 320                    |
| 800         | Apprendista III   | 117.1                     | 470                    |
| 1000        | Esperto I         | 100.0                     | 659                    |
| 1200        | Esperto II        | 86.5                      | 866                    |
| 1400        | Veterano I        | 75.9                      | 1091                   |
| 1600        | Veterano II       | 67.2                      | 1333                   |
| 1800        | Maestro           | 59.9                      | 1592                   |
| 2000        | Campione I        | 54.4                      | 2063                   |
| 2200        | Campione II       | 49.6                      | 2574                   |
| 2400        | Campione III      | 45.4                      | 3126                   |
| 2600        | Gran Campione     | 41.6                      | 3719                   |
| 2800        | Dominatore        | 38.2                      | 4354                   |
| 3000        | Leggenda          | 35.2                      | 5031                   |
| 4000        | Suprema Leggenda  | 25.1                      | 7764                   |

### Classifica?

**Livello Isola?**

$$
\text{Punteggio} = (\text{Valore blocchi isola}) \times \left( \frac{\sum \text{Elo}}{\text{1000 * maxMebri}} \right)
$$

**Evento Idola piu' bella**
  - Magari su yt con marcy
  - Un Tema per season
  - Le isole piu' belle della scorsa season rimangono in esposizione per la nuova 

----------

### Features?

- Custom Chest
    - *how*
      - contains just one type of element
      - start with a fixed capacity i.e. 50k 
      - upgrade it with game money until you get to Infinity
    - *pro* vs *contro* (**MUST HAVE**)

- Custom Hopper
    - *how*
      - you can link it to a Custom Chest
      - you can upgrade speed and range
      - upgrade it with game money
    - *pro*
      - lagga meno
      - fa molto figo
    - *contro*
      - levi molta redstone creativita'

- Stack Spanwer 
    - *how*
      - max 25 for block
      - mob stack non troppo eccessivo (non 10k se possibile)
    - *pro*
      - lagga meno
    - *contro*
      - levano belle missioni tipo i dischi

- Blocchi di valore
    - staccabbili in un blocco
    - *Idea altrenativa*
        - block holder infinito: ci puoi mettere tutti i blochi di un tipo
        - block holder x0.5: ci puoi mettere un K numeri di blocchi dove il loro valore e' * 0.5
        - block holder x0.75: ci puoi mettere un K numeri di blocchi dove il loro valore e' * 0.75
        - magari li metti in delle creates e quindi sono rari, ottenibbili o con i $ veri o missioni

- Minion ?
    - per automatizzare roba che disolito non puoi fare
        - farm automatica di blocchi al generatore 
        - farm automatica di legna (spacca albero e te lo ripianta)

----------

### Economia

main idea:
    - i blocchi si devono poter fare con missioni ripetibili 
    - i blocchi non dovrebbero poter essere shopparli allo shop
        - oppure so carissimi
    - in questo modo uno si deve fare le farm e usarle per salire di livello
    - i soldi li farmi per upgradare la tua isola e i vari items tipo casse, wand del sell all, etc
