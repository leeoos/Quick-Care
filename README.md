# Quick-Care

Quick Care is a Medical Booking Website that allows you to reserve a medical service in a hospital affiliated with the health system of Regione Lazio.
At the moment such a system does not exist, you have to confirm the appointment by phone.

## Project Structure

There are two main components 

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
## How To Test The Application
Once the database has been populated, three classes of booking codes will be made available, each relating to one of the following patients:

| Nome          | Cognome       | Codice fiscale   | Email             | Telefono      | Classe   |
|:-------------:|:-------------:|:----------------:|:-----------------:|:-------------:|:--------:|
| Lucilla       | Fragala       | FRGLLL25L65B960D | l.fraga@gmail.com | 555-72345     |    A     |
| Giusto        | Orsini        | RSNGST16B17H861J | g.orso@gmail.com  | 555-32163     |    B     |
| Placido       | Danesi        | DNSPCD43C29E910S | pla.dan@gmail.com | 555-93526     |    C     |

For each class there will be six prescriptions codes associated with the corresponding patient so that you can use one of that to make a reservation. A prescription code is something like ``Xn`` where ``X`` is the booking code class and n is a number from 1 to 6.

For example a reservation can be made for Lucilla Fragala filling the form with the given data and using the code ``A1``.

Once the 

