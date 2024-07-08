# sql2
--CREATE TABLE TEAMS (
--  c_code varchar(2) PRIMARY KEY,
--  country varchar(30) NOT NULL,
--  continent varchar(40) NOT NULL
  
--);



--INSERT INTO TEAMS VALUES ('G1', 'Ghana', 'Africa');
--INSERT INTO TEAMS VALUES ('N1', 'Nigeria', 'Africa');
--INSERT INTO TEAMS VALUES ('E2', 'Egypt', 'Africa');
--INSERT INTO TEAMS VALUES ('C9', 'Cameroon', 'Africa');
--INSERT INTO TEAMS VALUES ('K1', 'Kenya', 'Africa');


 --CREATE TABLE PLAYER (
--P_CODE varchar(4) PRIMARY KEY,
-- P_NAME varchar(30) NOT NULL,TEAMSTEAMS
--PRO_CLUB varchar(40) NOT NULL,
-- GOALS int  NULL,
-- COUNTRY_CODE varchar(2) NOT NULL,
-- CONSTRAINT Pk_TEAMS FOREIGN KEY (c_code) REFERENCES TEAMS(c_code) ON DELETE CASCADE ON UPDATE CASCADE
-- );

-- INSERT INTO PLAYER VALUES ('G002', 'Mochael Essien', 'Chelsea',4, 'G1');
 --INSERT INTO PLAYER VALUES ('N021', 'John Obi Mikel', 'Chelsea',1,'N1');
 --INSERT INTO PLAYER VALUES ('E039', 'Mohammed Zidane', 'Bayern Munich',2, 'E2');
 -- INSERT INTO PLAYER VALUES ('C087', 'Samwel E,too', 'Barcelona',5, 'C9');
-- INSERT INTO PLAYER VALUES ('G004', 'Stephen Appiah', 'Fernerbeche',2, 'G1');
-- INSERT INTO PLAYER VALUES ('E009', 'HASSAN OSAM', 'AL AJILI',0, 'E2');
INSERT INTO (P_CODE,  P_NAME, PRO_CLUB, COUNTRY_CODE) VALUES ('N032', 'JJ OKOCHA', 'CHELSEA', 'N1');

 


select  PLAYER.P_NAME, TEAMS.country, PLAYER.PRO_CLUB from PLAYER, TEAMS;
