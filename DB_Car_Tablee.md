

## Todo
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Tabella
| nome colonna | tipo di dato | attributi |
| ---- | ---- | ---- |
| id | INT | primary key, auto_increment |
| VIN | VARCHAR(17) | unique |
| brand | VARCHAR(128) | -- |
| model | VARCHAR(128) | -- |
| license_plate | VARCHAR(32) | unique , nullable |
| km | INT | default(0) |
| registration_date | DATE | nullable |
| displacement_cc | INT | nullable |
| horsepower | INT | -- |
| kw | INT | -- |
| fuel_type | VARCHAR(32) | -- |
| transmission | VARCHAR(32) | -- |
| Euro_class | TINYINT | -- |
| warranty | TINYINT | default(0) |
| price | INT | nullable |
| km/l | INT | -- |
| weight | INT | -- |
| category | VARCHAR(32) | -- |
| usage | VARCHAR(32) | -- |
| n_axes | TINYINT | -- |
| max_load_weight | INT | -- |
| seats | TINYINT | -- |
| decibel | INT | -- |
| co2_emission | INT | -- |
| tank_capacity | INT | -- |
| n_gears | TINYINT | -- |
| length | INT | -- |
| width | INT | -- |
| wheelbase | INT | -- |
| height | INT | -- |
| power_weight_ratio | INT | -- |
| colour_code | VARCHAR(32) | -- |


