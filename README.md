# Progetto Milano - Cortina 2026

Prova progettuale di **Analisi e Progettazione del Software** (A.A. 2025/2026)
Corso di Laurea in Informatica, Università degli Studi di Milano-Bicocca

Progetto di gruppo (4 persone) di analisi e progettazione, con modellazione UML, di un sistema informativo a supporto dell'organizzazione e della fruizione delle Olimpiadi Invernali Milano-Cortina 2026: gestione di attività ed eventi, allenamenti degli atleti, vendita e prenotazione di biglietti, autenticazione degli utenti.

> Questo repository contiene la **documentazione di analisi e progettazione**, non il codice dell'applicazione.

## Contenuto del repository

```
.
├── README.md
├── Progetto-Milano-Cortina-2026.pdf   # documento completo
└── diagrammi/                         # immagini .jpeg dei diagrammi del PDF
```

Il PDF raccoglie tutti gli artefatti. Alcuni diagrammi (in particolare casi d'uso e classi di progettazione) risultano poco leggibili a causa delle dimensioni: le versioni ad alta risoluzione sono nella cartella [`diagrammi/`](diagrammi/), con un nome file che inizia con il numero del capitolo del PDF.

## Il mio contributo

**Ho lavorato in particolare su:**

- **Caso d'uso `EffettuaPrenotazione`**: descrizione estesa, diagramma di sequenza di sistema, contratto dell'operazione e diagramma di sequenza di progettazione.
- **Modello di dominio** (in collaborazione con un altro componente del gruppo).
- **Diagramma delle classi di progettazione** (in collaborazione con un altro componente del gruppo).

**Parti svolte in comune dal gruppo:** caso d'uso `AutenticaUtente` (descrizione, SSD e sequenza di progettazione), contratti `InserisciAttività` e `PubblicaAttività`, diagrammi di attività, diagramma dei package, macchine a stati finiti, diagrammi di comunicazione, pattern GRASP e GoF.

## Indice degli artefatti e immagini corrispondenti

La colonna *Autore* indica se la parte è mia, svolta in comune o curata da un altro componente.

| Cap. | Artefatto | Autore | Immagine |
|---|---|---|---|
| 1 | Diagramma dei casi d'uso | Altro componente | [01-casi-uso.jpeg](diagrammi/01-casi-uso.jpeg) |
| 3 | SSD: AutenticaUtente (scenario principale) | In comune | [03-ssd-AutenticaUtente.jpeg](diagrammi/03-ssd-AutenticaUtente.jpeg) |
| 3 | SSD: AutenticaUtente (estensione credenziali errate) | In comune | [03-ssd-AutenticaUtente-estensione.jpeg](diagrammi/03-ssd-AutenticaUtente-estensione.jpeg) |
| 3 | SSD: AggiungiAllenamento | Altro componente | [03-ssd-AggiungiAllenamento.jpeg](diagrammi/03-ssd-AggiungiAllenamento.jpeg) |
| 3 | SSD: CancellaAllenamento | Altro componente | [03-ssd-CancellaAllenamento.jpeg](diagrammi/03-ssd-CancellaAllenamento.jpeg) |
| 3 | **SSD: EffettuaPrenotazione** | **Io** | [03-ssd-EffettuaPrenotazione.jpeg](diagrammi/03-ssd-EffettuaPrenotazione.jpeg) |
| 3 | SSD: PartecipaAllenamento | Altro componente | [03-ssd-PartecipaAllenamento.jpeg](diagrammi/03-ssd-PartecipaAllenamento.jpeg) |
| 5 | **Modello di dominio** | **Io (con un altro componente)** | [05-modello-dominio.jpeg](diagrammi/05-modello-dominio.jpeg) |
| 6 | Diagramma di attività: GestioneAllenamenti | In comune | [06-attivita-GestioneAllenamenti.jpeg](diagrammi/06-attivita-GestioneAllenamenti.jpeg) |
| 6 | Diagramma di attività: PrenotazioneBiglietto | In comune | [06-attivita-PrenotazioneBiglietto.jpeg](diagrammi/06-attivita-PrenotazioneBiglietto.jpeg) |
| 6 | Diagramma di attività: AutenticaUtente | In comune | [06-attivita-AutenticaUtente.jpeg](diagrammi/06-attivita-AutenticaUtente.jpeg) |
| 7 | Diagramma dei package | In comune | [07-package.jpeg](diagrammi/07-package.jpeg) |
| 8 | **Diagramma delle classi di progettazione** | **Io (con un altro componente)** | [08-classi-progettazione.jpeg](diagrammi/08-classi-progettazione.jpeg) |
| 9 | Sequenza: AutenticaUtente | In comune | [09-sequenza-AutenticaUtente.jpeg](diagrammi/09-sequenza-AutenticaUtente.jpeg) |
| 9 | Sequenza: AggiungiAllenamento | Altro componente | [09-sequenza-AggiungiAllenamento.jpeg](diagrammi/09-sequenza-AggiungiAllenamento.jpeg) |
| 9 | Sequenza: CancellaAllenamento | Altro componente | [09-sequenza-CancellaAllenamento.jpeg](diagrammi/09-sequenza-CancellaAllenamento.jpeg) |
| 9 | **Sequenza: EffettuaPrenotazione** | **Io** | [09-sequenza-EffettuaPrenotazione.jpeg](diagrammi/09-sequenza-EffettuaPrenotazione.jpeg) |
| 9 | Sequenza: PartecipaAllenamento | Altro componente | [09-sequenza-PartecipaAllenamento.jpeg](diagrammi/09-sequenza-PartecipaAllenamento.jpeg) |
| 10 | Macchina a stati: Biglietto | In comune | [10-stati-Biglietto.jpeg](diagrammi/10-stati-Biglietto.jpeg) |
| 10 | Macchina a stati: Attività | In comune | [10-stati-Attivita.jpeg](diagrammi/10-stati-Attivita.jpeg) |
| 11 | Comunicazione: InserisciAttività | In comune | [11-comunicazione-InserisciAttivita.jpeg](diagrammi/11-comunicazione-InserisciAttivita.jpeg) |
| 11 | Comunicazione: PubblicaAttività | In comune | [11-comunicazione-PubblicaAttivita.jpeg](diagrammi/11-comunicazione-PubblicaAttivita.jpeg) |

I capitoli 2 (casi d'uso in formato dettagliato), 4 (contratti) e 12 (pattern) sono solo testuali e si trovano nel PDF.

## Cosa contiene il progetto

- **Casi d'uso** in formato dettagliato (autenticazione, gestione degli allenamenti, prenotazione, partecipazione a un allenamento), con scenari principali, estensioni e requisiti speciali.
- **Diagrammi di sequenza di sistema** e **contratti** delle operazioni di sistema.
- **Modello di dominio** e **diagrammi di attività**.
- **Progettazione**: diagramma dei package (architettura a strati UI / Controller / Domain / Services), diagramma delle classi di progettazione, diagrammi di sequenza e di comunicazione, macchine a stati finiti.
- **Pattern**: Singleton (GoF); Information Expert, Creator, Low Coupling, High Cohesion, Controller, Polymorphism (GRASP).

## Strumenti

- UML: Visual Paradigm Community Edition

## Note

Il progetto è stato sviluppato come prova progettuale universitaria. Gli artefatti riflettono la versione consegnata.
