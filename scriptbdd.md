Requêtes utilisées pour le MVP :

CREATE TABLE Users(idUsers INT NOT NULL PRIMARY KEY AUTO_INCREMENT,firstName VARCHAR(100) NOT NULL,lastName VARCHAR(100) NOT NULL,pseudo VARCHAR(45) NOT NULL,promo VARCHAR(45),birthDate DATE NOT NULL, working BOOLEAN NOT NULL, exp INT NOT NULL, simplon BOOLEAN NOT NULL,curriculum TEXT,email TEXT NOT NULL,pass TEXT NOT NULL)