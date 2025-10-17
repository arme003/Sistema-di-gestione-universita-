# Sistema di Gestione Università

## Descrizione
Questo progetto implementa un semplice sistema di gestione per una università utilizzando la programmazione orientata agli oggetti (OOP) in Python.  
Viene definita una classe base `Persona` e diverse classi derivate che rappresentano ruoli comuni in università: Studente, Professore, Ricercatore, Segretario e Tecnico.

Ogni classe derivata estende la classe base aggiungendo attributi specifici e un metodo `printa()` per stampare tutte le informazioni dell’oggetto in modo leggibile.

## Classi

### Persona
- Attributi:
  - `nome`: nome della persona
  - `cognome`: cognome della persona
  - `eta`: età
- Metodo:
  - `descrivi()`: stampa nome, cognome ed età

### Studente
- Attributi aggiuntivi:
  - `corso_di_laurea`: corso di laurea dello studente
  - `voti`: lista dei voti dello studente
- Metodo:
  - `printa()`: stampa nome, cognome, età, corso di laurea e voti

### Professore
- Attributi aggiuntivi:
  - `materia_insegnata`: materia insegnata dal professore
  - `anni_di_esperienza`: anni di esperienza
- Metodo:
  - `printa()`: stampa tutte le informazioni

### Ricercatore
- Attributi aggiuntivi:
  - `campo_di_ricerca`: campo di ricerca
  - `progetti`: lista dei progetti
- Metodo:
  - `printa()`: stampa tutte le informazioni

### Segretario
- Attributi aggiuntivi:
  - `ufficio`: numero dell’ufficio
  - `telefono`: numero di telefono
- Metodo:
  - `printa()`: stampa tutte le informazioni

### Tecnico
- Attributi aggiuntivi:
  - `reparto`: reparto di lavoro
  - `strumenti`: lista di strumenti utilizzati
- Metodo:
  - `printa()`: stampa tutte le informazioni

## Dati di esempio

### Studenti
- Mario Rossi, 21 anni, Informatica, voti: [28, 30, 27]  
- Giulia Bianchi, 22 anni, Ingegneria Gestionale, voti: [30, 26, 29]  

### Professori
- Anna Verdi, 45 anni, Matematica, 20 anni di esperienza  
- Luca Neri, 50 anni, Fisica, 25 anni di esperienza  

### Ricercatori
- Fabio Gialli, 35 anni, Intelligenza Artificiale, progetti: ['Chatbot', 'Vision AI']  
- Sara Blu, 38 anni, Robotica, progetti: ['Drone', 'Braccio Robotico']  

### Segretari
- Carla Neri, 40 anni, ufficio A1, telefono 0123456789  
- Paolo Rossi, 42 anni, ufficio B2, telefono 0987654321  

### Tecnici
- Marco Gialli, 30 anni, Laboratorio, strumenti: ['Microscopio', 'Oscilloscopio']  
- Elisa Marrone, 28 anni, Informatica, strumenti: ['Server', 'Router']  

## Output desiderato

Studente: Mario Rossi, età 21, corso di laurea Informatica, voti [28, 30, 27]  
Studente: Giulia Bianchi, età 22, corso di laurea Ingegneria Gestionale, voti [30, 26, 29]  
Professore: Anna Verdi, età 45, materia insegnata Matematica, anni di esperienza 20  
Professore: Luca Neri, età 50, materia insegnata Fisica, anni di esperienza 25  
Ricercatore: Fabio Gialli, età 35, campo di ricerca Intelligenza Artificiale, progetti ['Chatbot', 'Vision AI']  
Ricercatore: Sara Blu, età 38, campo di ricerca Robotica, progetti ['Drone', 'Braccio Robotico']  
Segretario: Carla Neri, età 40, ufficio A1, telefono 0123456789  
Segretario: Paolo Rossi, età 42, ufficio B2, telefono 0987654321  
Tecnico: Marco Gialli, età 30, reparto Laboratori
