# Calendario & Todo App

Applicazione web avanzata per la gestione di calendario, eventi e task con interfaccia desktop e mobile ottimizzata.

## Descrizione

Sistema completo di gestione produttività che combina:
- Calendario mensile interattivo
- Lista eventi e scadenze
- Board Kanban per gestione todo
- Statistiche e analisi produttività
- Timer e tracking tempo
- Modalità focus
- Sistema di auto-creazione promemoria intelligenti

## Caratteristiche Principali

### Gestione Eventi
- Tre tipi di elementi: Appuntamenti, Scadenze, Todo
- Categorie personalizzabili (Lavoro, Personale, Studio, Salute)
- Livelli di priorità (Alta, Media, Bassa)
- Sistema di tag per organizzazione avanzata

### Vista Calendario
- Navigazione mensile intuitiva
- Visualizzazione eventi per giorno
- Indicatori visivi per giorni con eventi
- Selezione rapida date

### Vista Todo Kanban
- 4 colonne di stato: Da fare, In corso, Completati, In pausa
- Drag & drop per spostare task tra colonne
- Tempo stimato e tempo effettivo
- Tag e categorizzazione

### Timer & Tracking
- Timer integrato per ogni task
- Tracking automatico tempo speso
- Modalità focus per concentrazione massima
- Statistiche tempo per categoria

### Statistiche
- Produttività giornaliera e settimanale
- Distribuzione per categoria
- Grafici tempo stimato vs completato
- Andamento settimanale completamenti

### Auto-Creazione Intelligente
- Promemoria automatici per scadenze imminenti
- Todo di preparazione per eventi importanti
- Configurazione personalizzabile
- Suggerimenti contestuali basati su tipo evento

### Persistenza Dati
- Salvataggio automatico in localStorage
- Export/Import dati in JSON
- Backup completo sistema
- Gestione dati integrata

## Tecnologie Utilizzate

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Tailwind CSS 3.x (CDN)
- **Storage**: Browser localStorage API
- **Architettura**: Single Page Application (SPA)

## Versioni

### Desktop (index.html)
- Layout ottimizzato per schermi grandi
- Vista kanban con 4 colonne affiancate
- Pannelli laterali e modali centrali
- Filtri avanzati sempre visibili

### Mobile (mobile.html)
- Design mobile-first responsive
- Bottom navigation bar
- Drawer menu laterale
- Modal bottom-sheet
- Vista kanban a tab singola
- Touch-optimized interface

## Installazione e Uso

### Uso Locale

1. Clona il repository:
```bash
git clone https://github.com/tuousername/calendario-todo-app.git
cd calendario-todo-app
