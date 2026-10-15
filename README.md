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
└── diagrammi/                         # immagini .jpg dei diagrammi del PDF
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
| 1 | Diagramma dei casi d'uso | Altro componente | [01-casi-uso.jpg](diagrammi/01-casi-uso.jpg) |
| 3 | SSD: AutenticaUtente (scenario principale) | In comune | [03-ssd-AutenticaUtente.jpg](diagrammi/03-ssd-AutenticaUtente.jpg) |
| 3 | SSD: AutenticaUtente (estensione credenziali errate) | In comune | [03-ssd-AutenticaUtente-estensione.jpg](diagrammi/03-ssd-AutenticaUtente-estensione.jpg) |
| 3 | SSD: AggiungiAllenamento | Altro componente | [03-ssd-AggiungiAllenamento.jpg](diagrammi/03-ssd-AggiungiAllenamento.jpg) |
| 3 | SSD: CancellaAllenamento | Altro componente | [03-ssd-CancellaAllenamento.jpg](diagrammi/03-ssd-CancellaAllenamento.jpg) |
| 3 | **SSD: EffettuaPrenotazione** | **Io** | [03-ssd-EffettuaPrenotazione.jpg](diagrammi/03-ssd-EffettuaPrenotazione.jpg) |
| 3 | SSD: PartecipaAllenamento | Altro componente | [03-ssd-PartecipaAllenamento.jpg](diagrammi/03-ssd-PartecipaAllenamento.jpg) |
| 5 | **Modello di dominio** | **Io (con un altro componente)** | [05-modello-dominio.jpg](diagrammi/05-modello-dominio.jpg) |
| 6 | Diagramma di attività: GestioneAllenamenti | In comune | [06-attivita-GestioneAllenamenti.jpg](diagrammi/06-attivita-GestioneAllenamenti.jpg) |
| 6 | Diagramma di attività: PrenotazioneBiglietto | In comune | [06-attivita-PrenotazioneBiglietto.jpg](diagrammi/06-attivita-PrenotazioneBiglietto.jpg) |
| 6 | Diagramma di attività: AutenticaUtente | In comune | [06-attivita-AutenticaUtente.jpg](diagrammi/06-attivita-AutenticaUtente.jpg) |
| 7 | Diagramma dei package | In comune | [07-package.jpg](diagrammi/07-package.jpg) |
| 8 | **Diagramma delle classi di progettazione** | **Io (con un altro componente)** | [08-classi-progettazione.jpg](diagrammi/08-classi-progettazione.jpg) |
| 9 | Sequenza: AutenticaUtente | In comune | [09-sequenza-AutenticaUtente.jpg](diagrammi/09-sequenza-AutenticaUtente.jpg) |
| 9 | Sequenza: AggiungiAllenamento | Altro componente | [09-sequenza-AggiungiAllenamento.jpg](diagrammi/09-sequenza-AggiungiAllenamento.jpg) |
| 9 | Sequenza: CancellaAllenamento | Altro componente | [09-sequenza-CancellaAllenamento.jpg](diagrammi/09-sequenza-CancellaAllenamento.jpg) |
| 9 | **Sequenza: EffettuaPrenotazione** | **Io** | [09-sequenza-EffettuaPrenotazione.jpg](diagrammi/09-sequenza-EffettuaPrenotazione.jpg) |
| 9 | Sequenza: PartecipaAllenamento | Altro componente | [09-sequenza-PartecipaAllenamento.jpg](diagrammi/09-sequenza-PartecipaAllenamento.jpg) |
| 10 | Macchina a stati: Biglietto | In comune | [10-stati-Biglietto.jpg](diagrammi/10-stati-Biglietto.jpg) |
| 10 | Macchina a stati: Attività | In comune | [10-stati-Attivita.jpg](diagrammi/10-stati-Attivita.jpg) |
| 11 | Comunicazione: InserisciAttività | In comune | [11-comunicazione-InserisciAttivita.jpg](diagrammi/11-comunicazione-InserisciAttivita.jpg) |
| 11 | Comunicazione: PubblicaAttività | In comune | [11-comunicazione-PubblicaAttivita.jpg](diagrammi/11-comunicazione-PubblicaAttivita.jpg) |

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
