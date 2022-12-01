## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: Cars

    id: BIGINT, PK (SE NON SONO COMPRESE IN PK => AUTO_INCREMENT, UNIQUE, NOTNULL)
    brand: VARCHAR (25), NOTNULL
    model: VARCHAR (30), NOTNULL
    engine: VARCHAR (30), NULL
    color: VARCHAR (25), NULL
    seats: TINYINT, NULL
    km: SMALL / MEDIUMINT, NULL
    price: DECIMAL(8,2), NULL
    year: YEAR, NULL
    description: TEXT, NULL
    notes: TEXT, NULL 
    
