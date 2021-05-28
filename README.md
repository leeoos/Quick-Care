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
Once the database is populated

| Nome          | Cognome       | Codice fiscale   |
| ------------- |:-------------:| :---------------:|
| Lucilla       | Fragala       | FRGLLL25L65B960D |
| Giusto        | Orsini        | RSNGST16B17H861J |
| Placido       | Danesi        | DNSPCD43C29E910S |