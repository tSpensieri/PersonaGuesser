# PersonaGuesser

## Descrizione

PersonaGuesser è un'applicazione innovativa che utilizza l'intelligenza artificiale per generare indizi su persone famose. Inserisci il nome di una persona famosa, e l'applicazione produrrà una serie di indizi che aiuteranno l'utente a indovinare di chi si tratta. Questo progetto sfrutta le API di OpenAI integrate con Spring AI nel backend e presenta un'interfaccia utente moderna e reattiva sviluppata con Astro e Tailwind CSS.

## Funzionalità

- **Inserimento Nome**: Gli utenti possono inserire il nome di una persona famosa.
- **Generazione di Indizi**: L'applicazione utilizza l'intelligenza artificiale per elaborare e restituire indizi utili che descrivono la persona selezionata.
- **Interfaccia Utente**: Un'interfaccia semplice e intuitiva per facilitare l'uso dell'applicazione.
- **Modalità di Gioco**: Include una modalità di gioco che sfida gli utenti a indovinare il più velocemente possibile per accumulare punti.

## Tecnologie Utilizzate

### Frontend

- **[Astro](https://astro.build/)**: Un framework all-in-one per la costruzione di siti web veloci e moderni.
- **[Tailwind CSS](https://tailwindcss.com/)**: Un framework CSS utility-first per un design rapido e reattivo.

### Backend

- **[Spring Boot](https://spring.io/projects/spring-boot)**: Framework per facilitare la configurazione e il deployment di applicazioni basate su Spring.
- **[Spring AI](https://spring.io/projects/spring-ai)**: Modulo di Spring per integrare facilmente funzionalità di intelligenza artificiale.

## Struttura del Progetto

- [PersonaGuesser-Frontend](https://github.com/tSpensieri/PersonaGuesser-Frontend/tree/e64eb2dfa4b1d06ec7522c1467a1854a6a7861d5): Codice sorgente del frontend.
- [PersonaGuesser-Backend](https://github.com/tSpensieri/PersonaGuesser-Backend/tree/e9cc1bf6ace09989f34807a18abae5790f91e4c0): Codice sorgente del backend.

## Come Iniziare

### Clonazione del Repository

Clona il repository principale e i submodules per ottenere il codice sorgente del frontend e del backend.

```bash
git clone --recurse-submodules https://github.com/tSpensieri/PersonaGuesser.git
cd PersonaGuesser
```

### Installazione dipendenze

#### Frontend

Naviga nella directory del frontend e installa le dipendenze.

```bash
cd PersonaGuesser-Frontend
npm install
# o
yarn install
# o
bun i
```

#### Backend

Naviga nella directory del backend e installa le dipendenze.

```bash
cd ../PersonaGuesser-Backend
./mvnw clean install
```

### Avvio dell'Applicazione

#### Avvio del Frontend

Assicurati di essere nella directory del frontend.

```bash
cd PersonaGuesser-Frontend
npm run dev
# o
yarn dev
# o
bun run dev
```

Il frontend sarà disponibile su `http://localhost:3000`.

#### Avvio del Backend

Assicurati di essere nella directory del backend.

```bash
cd ../PersonaGuesser-Backend
./mvnw spring-boot:run
```

Il backend sarà disponibile su http://localhost:8080.

## Contribuire

Se sei interessato a contribuire al progetto PersonaGuesser, considera di:

- Forkare il repository.
- Creare un branch per la tua feature (git checkout -b feature/miaFeature).
- Fare commit delle tue modifiche (git commit -am 'Aggiunta una nuova feature').
- Fare push al branch (git push origin feature/miaFeature).
- Aprire una pull request.

## Licenza

Questo progetto è rilasciato sotto la licenza MIT.

## Contatti

Per maggiori informazioni, contattami via github o segui il progetto su https://github.com/tSpensieri/PersonaGuesser.

Grazie per aver utilizzato PersonaGuesser!
