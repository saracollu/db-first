cars table

- id INT PK NN UNIQUE INDEX AI
- brand VARCHAR(15) NN
- model VARCHAR(15) NN
- series VARCHAR(10) NN UNIQUE INDEX
- immatricolation YEAR NN
- alimentation VARCHAR (50) NN 
- cyl SMALLINT NN
- power_kw SMALLINT NN
- color VARCHAR (20)  NN
- gadgets VARCHAR (255) NULL
- km MEDIUMINT NN
- price DECIMAL(10, 2) NN
- decription TEXT NULL
- targa VARCHAR(10) NULL
- isavailable TINYINT NN

