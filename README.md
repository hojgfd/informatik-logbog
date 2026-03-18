# Logbog 28/8/2024
## Tello dronerne
### Vi er blevet introduceret til et projekt, hvor vi skal arbejde med Tello droner og styre dronernes bevægelse gennem programmering i Python.

## 3-lags-modellen
### Vi har lært om 3-lags-modellen og hvordan man kan dele et it-system op i tre dele.


## Innovation (4p)
<img width="675" height="584" alt="image" src="https://github.com/user-attachments/assets/67932db1-8ee6-499d-8239-7780e7d225e8" />

### Vi skal bruge 4P-modellen for innovation som består af denne proces: Produkt-innovation, Proces-innovation, Positions-innovation og Paradigme-innovation

## Idégenerering til projekt dronecontroller
### Vi har brugt idégenerering til at komme på forskellige idéer til hvordan vi skal styre en tello drone såsom at lave et CO2-opfanger system, der tjekker CO2 niveauet for at se om man indånder eller udånder og så ville dronen rykke frem og tilbage baseret på den data.


# Logbog 10/1/2025
## Kryptografi
### Vi er begyndt på et nyt emne kryptografiog lært om de forskellige metoder der bruges til enkryptering og dekryptering, bl.a. Caesar Cipher og hashing. Vi gik ud fra et eksempel med "Alice og Bob" (A og B), der kommunikerer med kryptografi, for at få en bedre forståelse for det der sker gennem krypteringen.

### Vi har begyndt på et nyt projekt med kryptografi, hvor vi tager udgangspunkt i Alice og Bob scenariet og demonstrerer udvekslingen af beskeder fra A til B.

# CIA-Modellen
<img width="750" height="419" alt="image" src="https://github.com/user-attachments/assets/05cc1c54-bf4e-4930-ad32-1bec50507c74" />


# Logbog 13/03/2025
## Cybermesterskaberne
### Lavede opgaverne AES Decryption, The professors last note og Find frontdoor, for at kvalificere mig til DDC Junior. Modtog en email og meldte mig til det.

# Logbog 27/3/2025
## Cybersecurity webstuff
### Sårbarhed i flask + sqlite (exploits er muligt især hvis sat op forkert)
### Bug bounty
### Responsible disclosure
### The seven layers of the OSI model (from the bottom): Physical - Data link - Network - Transport - Session - Presentation - Application
###
### Vi lærte om curl, nmap og ncat og afprøvede dem. For eksempel var vi to og to hvor den ene satte en listener op med ncat og den anden connectede til den første persons ip med ncat, så man kunne skrive sammen i terminalen. 
### NOTER (credit Mark Robert Nygaard Moore AKA. Robotto fra github.com):
### Nmap viser åbne porte på en target IP
### eksempel: nmap 10.148.132.76
### curl forbinder til webservere og viser rådata
### eksempel: curl orion.moore.dk
### nc til rå forbindelser mellem maskiner (TCP/UDP) – kan både lytte og ringe
### Vi lærte også lidt om SQL Injection 💉, som ligesom steroider er at inject ulovligheder ind i noget, i dette tilfælde en sql database, med simple cases såsom at input noget sql kode der altid er sandt som ' or '1' = '1, som får en dårligt implementeret sql database til at leak alt dataen 

# Logbog 05/05/2025
## Vi lærte om teachable machine, hvor vi trænede en AI model med billeder og lydklip, som vi derefter importerede ind i p5.js, så vi kunne skrive noget kode med brug af AI.

# Logbog 12/5/2025
## Vi startede timen ud med et recap om informatik, hvor vi repeterede 3-lags-modellen og de tidligere projekter vi har lavet i 2.g.
## Vi arbejdede videre med teachable machine, med fokus på kode-delen.

# Logbog 21/8/2025
## Det var den første informatik lektion i 3.g, så vi opsummerede det vi havde lavet i 2.g
## Emner vi opsummerede:
### 3-lags modellen
<img width="650" height="652" alt="image" src="https://github.com/user-attachments/assets/2d0b5444-deab-4ecc-b847-16d9d673ec9b" />


## IT System
### Server client
#### Server
#### Udstiller endpoints der giver clients(s) mulighed for at lagre og læse data

### API
### -Get
### -Put
### -Post
### -Store

### Client -> JSON -> Server (JSON virker som et API, der sender data frem og tilbage mellem server og client)

### Data sink: enhed der får data fra serveren
### Vi lavede en gruppe til vores første projekt i 3.g

# Logbog 27/08/2025
## Projektopstart DATA-API-projekt
### Vi klargjorte Miro, trello og github for versionsstyring og projektstyring
### Vi beskrev vores koncept og overvejede forskellige data der skulle gemmes og sendes mellem klient og server
### Vi lavede skitser over de vigtige ting vores program skulle kunne og testede nogle flask sqlite eksempler ud for at få noget til at køre

# 27-08-2025

### Alle er til stede.


### Udvalg af projektide
Det er valgt at arbejde med luftsensor:

<img width="630" height="363" alt="image" src="https://github.com/user-attachments/assets/d3a16b97-2412-4c18-a176-7cdb8df2372f" />


### Systemopbygningsovervejelser
Der er lavet en rough sketch af hvordan it-systemet skal fungere:

<img width="1139" height="918" alt="image" src="https://github.com/user-attachments/assets/4c3f548c-4169-4a25-b425-532d6c518852" />


Samt foreløbigt udvalgt hvad sensorer skal opsamle af data:

<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/6a35bd93-1803-4802-884f-2d934d181b88" />

Hertil er der også lavet et eksempel af front end design, altså hvordan en client visuelt skal få dataen fremvist fra server:

<img width="700" height="311" alt="image" src="https://github.com/user-attachments/assets/4b8ddef2-c431-435c-b988-56b870e4f993" />


### JSON opbyggelse

<img width="621" height="307" alt="image" src="https://github.com/user-attachments/assets/8e1b533c-ccee-42a0-a28f-0adb5e64b8ae" />

# 01-09-2025

Efter vi fik vores ide med at lave luftsensor undersøgte vi om vi havde sensor på skolen. 

Vi fandt ud af at Mark havde en Sensor der måler CO2 + Luftfugtighed + Temperatur: Scd40 som vi måt låne. 

Vi lavede et UI til vores program og testede sensor


# 17-09-2025
Delt trello link med Mark

Få data med ESP32 virker nu. Dette tog lidt lang tid.

UI til /lokaler er nu lavet - dog mangler vi at benytte værdier fra sensor

UI til specifikke lokaler er undervejs

UI til varme-koldest er undervejs


# 24-09-2025

Alle var til stede

Historik over datamålinger og database dertil er lavet. En minimum viable UI er også lavet til dette, og det kører på pythonAnywhere



Der er lavet UI til grafer. Nu mangler der bare at benytte de faktiske data - samt at indkooperere det i den generelle UI for specifik lokale.



Generelt små rettelser af kode




# 27-10-2025

Lært om normalformer 1, 2 & 3


Revideret database struktur, så det følger normalform 2:

<img width="820" height="941" alt="image" src="https://github.com/user-attachments/assets/3d29e00d-879c-4031-a83a-c4a5babe57ba" />



Opdateret database strukturen i koden også.


# 04-11-2025


Ramsen og Rasmus er til stede


Ramsen har foretaget brugertest med Lukas. Typen af brugertest var hvor han skulle fuldføre opgaver/objectives.



Rasmus har desigent, laserskåret, samlet og testet iteration 2 af elektronik boks & lavet iteration 3 af selve sliding door. Se evt. trello for flere billeder.


<img width="711" height="633" alt="image" src="https://github.com/user-attachments/assets/1366104b-957d-4124-88b1-fc2fdd534fdb" />


# 05-11-2025

Alle er her 


Ramsen har forsøgt at få ESP32 til at virke på Marks internet. Det fungerer ikke helt endnu.
Ramsen har været i gang med at få udskiftet arduinoen, da dens mikrousb intake knækkede af.

Rasmus har fået gjort så lokaleSpecifik nu displayer faktisk data i de 3 grafer. Det fungerer.





# Logbog 03/12/2025
## Digital logic sim
### Lavede forskellige gates på digital logic sim som er et simpelt, interaktivt program, der fungerer som en digital logiksimulator til at lære om, hvordan logiske porte og computerprocessorer fungerer.
### AND: <img width="1257" height="402" alt="image" src="https://github.com/user-attachments/assets/46d2ad6a-98ea-406d-b4e8-c1dc92a65e4c" />
### NOT: <img width="1084" height="191" alt="image" src="https://github.com/user-attachments/assets/03ca44e5-3410-48ee-825a-97b667362406" />
### OR: <img width="2531" height="536" alt="image" src="https://github.com/user-attachments/assets/583ba956-62c7-463f-bdb2-0214854813c9" />
### XOR: <img width="2559" height="792" alt="image" src="https://github.com/user-attachments/assets/1be2b3c8-451d-418d-81ba-35c675444140" />
### ADDER: <img width="2559" height="1221" alt="image" src="https://github.com/user-attachments/assets/f914f73e-6e91-430c-bb4e-6a6f76470108" />
### 4-BIT-ADDER: <img width="2553" height="1351" alt="image" src="https://github.com/user-attachments/assets/35a23031-e88a-4c43-8ecc-f7c810d6dad0" />
### 8-BIT-ADDER: <img width="2271" height="1299" alt="image" src="https://github.com/user-attachments/assets/b66cdc49-56da-4e83-b242-084d72563a25" />
### 16-BIT-ADDER: <img width="2251" height="1193" alt="image" src="https://github.com/user-attachments/assets/af92d449-3765-4564-b68c-0b1f47c707dc" />
###

# Logbog 16/1/2026
## Vi har besøgt CAPRA robotics, der har revolutioneret udendørs robotter og set hvordan de har udviklet forskellige robotter.

# Logbog 20/01/2026
## Vi har startet på et nyt projekt om robotter hvor vi har valgt at arbejde om saltning af veje og at gøre det til en mere automatiseret proces. Vi har

# Logbog 05/02/2026
## Vi har lånt en Maqueen robot, esp32, samt en temperatur og luftfugtighedssensor, som vi kan bruge til at beregne hvor meget salt der er brug for på et specifikt sted. Idéen er at vi får robotten til at køre rundt på vejene og indsamle temperatur og luftfugtighedsdata ved forskellige steder og sende dataen til en hjemmeside, sådan brugeren kan se hvor meget salt vejene har brug for.

# Logbog 05/03
## Vi har lavet produktet færdigt, ved at udvikle hjemmesiden, host den vha. PythonAnywhere, samt sætte esp32 og sensoren fast på maqueen robotten sådan vi kan indsamle dataen.

# Logbog 11/03/2026
## I dag har vi lavet vores rapport i vores robot projekt, videopræsentation og afleveret

# Logbog 12/03/2026
## Data brokers mini-forløb
### Vi har set en youtube video om data brokers fra last week tonight : https://www.youtube.com/watch?v=wqn3gR1WTcA
### Videoen handlede om hvordan ens data bliver indsamlet og hvor let det er at få fat på. De brugte forskellige eksempler til at sætte i perspektiv hvordan det er muligt at identificere en person og hans søgehistorik, hobbyer, interesser osv.
