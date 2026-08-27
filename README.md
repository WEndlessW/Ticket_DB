# Ticket_DB
## Popis
Tento projekt představuje návrh a vytvoření **relační databáze** pro zakoupení ticketů na e-sport zápas. Databáze umožňuje evidovat týmy, zápasy, zákazníky a zakoupené tikety.

Cílem projektu je ukázat principy návrhu databází, práci s **relacemi mezi tabulkami** a využití **cizích klíčů**.

## Programy
Při tvoření této databáze jsem použil čistě **MySQL Workbench** *(verze MySQL Workbench 8.0.47, verze MySQL Server 8.0.46)*.

## Architektura databáze
### Tabulky
Databáze se skládá ze čtyř hlavních tabulek *(game, squad, ticket, person)*.

### Vztahy mezi tabulkami
Squad ↔ Game → 1 Person ↔ Ticket → 1 Game ↔ Ticket → 1

## ER Diagram
<p align="center">
  <img width="690" height="450" src="https://github.com/WEndlessW/Ticket_DB/blob/main/screenshot_of_ticket_db.png">
</p>

**[Pokud si chceš stáhnout .mwb (Project File for MySQL Workbench) soubor ER diagramu klikni ZDE!](https://github.com/WEndlessW/Ticket_DB/blob/64403d595ab872c42fe8936beb66a61dc3bc4baa/ER-Diagram%20Datab%C3%A1ze%20Ticket%20DB/ER_Diagram_Ticket_DB.mwb)**


## Jak projekt spustit?
Otevřete **MySQL Workbench**, vytvořte databázi *(např. tickets_db)*, spusťte **SQL skript**. A databáze by měla být plně připravena k použití.  **[Pro SQL Skript Klikni ZDE!](https://github.com/WEndlessW/Ticket_DB/blob/1a7b43b1c39631fed60b2f19d793226b58e75630/SQL%20Datab%C3%A1ze%20Ticket%20DB/ticket_db.sql)**

## Důvod vzniku databáze
Tato databáze vznikla pouze za účelem splnění druhého ročníku **VOŠ** :)

## Autor
Projekt zpracoval **Endless** do předmětu **DBS**.

**- Endless 2026**
