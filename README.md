# Quick-Care

Quick Care is a Medical Booking Website that allows you to reserve a medical service in a hospital affiliated with the health system of the Lazio Region

## How To Build And Populate The Database
To build the database in a postgres system run:

```
CREATE DATABASE quickcare;

\i QuickCare/Database/database.sql
```

To populate the database:

```
\i QuickCare/Database/data_samples.sql
```
## How To Test The Code
once the database has been populated, three classes of booking codes will be made available, each relating to one of the following patients:

| Nome          | Cognome       | Codice fiscale   | Email             | Telefono      | Classe Codice   |
|:-------------:|:-------------:|:----------------:|:-----------------:|:-------------:|:---------------:|
| Lucilla       | Fragala       | FRGLLL25L65B960D | l.fraga@gmail.com | 555-72345     |        A        |
| Giusto        | Orsini        | RSNGST16B17H861J | g.orso@gmail.com  | 555-32163     |        B        |
| Placido       | Danesi        | DNSPCD43C29E910S | pla.dan@gmail.com | 555-93526     |        C        |