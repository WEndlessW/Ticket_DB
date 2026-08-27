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
![PNG ER Diagramu Databáze](https://github.com/WEndlessW/Ticket_DB/blob/main/screenshot_of_ticket_db.png)

##Jak projekt spustit?
Otevřete **MySQL Workbench**, vytvořte databázi *(např. tickets_db)*, spusťte **SQL skript**. A databáze by měla být plně připravena k použití. [Go to parent folder README](SQL-Databáze-Ticket-DB/ticket_db.sql)
