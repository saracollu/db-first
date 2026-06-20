cars table

- id INT PK NN UNIQUE INDEX AI
- brand VARCHAR(15) NN
- model VARCHAR(15) NN
- series VARCHAR(10) NN UNIQUE INDEX
- immatricolation YEAR NN
- alimentation VARCHAR (50) NN 
- cyl SMALLINT
- power_kw SMALLINT
- color VARCHAR (20)
- gadgets VARCHAR (255)
- km MEDIUMINT
- price DECIMAL(10, 2)
- decription TEXT
- targa VARCHAR(10)
- isavailable TINYINT

