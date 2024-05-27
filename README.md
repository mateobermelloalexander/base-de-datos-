# trabajo-en-clase-semana-8

## la funcion count

### Creacion de la tabla ##'client'##

El siguiente codigo genera la siguiguiente tabla

'''

CREATE TABLE IF NOT EXIT client(

id SERIAL,

nui VARCHAR (100) NOT NULL,

fullname VARCHAR (100)  NOT NULL

phone VARCHAR (10),

type-of-client VARCHAR (50) DEFAULT 'BASIC',

credit_limit DECIMAL(7,2)

);

### Intersection de datos
('NUI123456', 'John Doe', '1234567890', 'PREMIUM', 5000.00),

('NUI123457', 'Jane Smith', '1234567891', 'BASIC', 3000.00),

('NUI123458', 'Robert Brown', '1234567892', 'GOLD', 7000.00),

('NUI123459', 'Emily Davis', '1234567893', 'BASIC', 1500.00),

('NUI123460', 'Michael Johnson', '1234567894', 'PLATINUM', 10000.00),

('NUI123461', 'Sarah Wilson', '1234567895', 'BASIC', 2500.00),

('NUI123462', 'David Martinez', '1234567896', 'GOLD', 8000.00),

('NUI123463', 'Laura Clark', '1234567897', 'PREMIUM', 6000.00),

('NUI123464', 'James Lee', '1234567898', 'BASIC', 2000.00),

('NUI123465', 'Linda Harris', '1234567899', 'PREMIUM', 5500.00);

### consulta de datos 
## count

'''



