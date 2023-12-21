 > ## Ödev 8 Sorular
 >1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
>
>2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
>
>3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
>
>4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

## Tablo oluşturma

CREATE TABLE employee (
	id INTEGER PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);

## veri ekleme

insert into employee (id, name, birthday, email) values (1, 'Killy', '1927-02-05', 'kcollacombe0@jalbum.net');
insert into employee (id, name, birthday, email) values (2, 'Karly', '2001-06-04', 'ktreagus1@google.es');
insert into employee (id, name, birthday, email) values (3, 'Monte', '1953-10-11', 'mengeham2@smh.com.au');
insert into employee (id, name, birthday, email) values (4, 'Nat', '1988-07-11', 'nmarte3@japanpost.jp');
insert into employee (id, name, birthday, email) values (5, 'Demott', '1956-09-20', 'dwiz4@pinterest.com');
insert into employee (id, name, birthday, email) values (6, 'Harli', '1989-09-25', 'hlie5@yellowbook.com');
insert into employee (id, name, birthday, email) values (7, 'Nil', '1902-11-08', 'nkeeltagh6@home.pl');
insert into employee (id, name, birthday, email) values (8, 'Wilma', '1910-11-17', 'wlandrean7@sciencedaily.com');
insert into employee (id, name, birthday, email) values (9, 'Isis', '1918-06-27', 'icescon8@dailymotion.com');
insert into employee (id, name, birthday, email) values (10, 'Shalna', '1937-11-22', 'sjerred9@elegantthemes.com');
insert into employee (id, name, birthday, email) values (11, 'Geoff', '1917-12-26', 'gatkirka@ed.gov');
insert into employee (id, name, birthday, email) values (12, 'Link', '1938-04-03', 'lbagnallb@kickstarter.com');
insert into employee (id, name, birthday, email) values (13, 'Denyse', '1919-10-03', 'droderickc@businessinsider.com');
insert into employee (id, name, birthday, email) values (14, 'Hal', '1993-07-27', 'hdimmickd@google.com.au');
insert into employee (id, name, birthday, email) values (15, 'Kissiah', '1952-12-01', 'kclynmanse@themeforest.net');
insert into employee (id, name, birthday, email) values (16, 'Ignaz', '1953-03-01', 'idodmanf@wordpress.com');
insert into employee (id, name, birthday, email) values (17, 'Deane', '1931-04-03', 'drubartellig@imdb.com');
insert into employee (id, name, birthday, email) values (18, 'Violante', '1951-07-13', 'vcrawleyh@youtu.be');
insert into employee (id, name, birthday, email) values (19, 'Corrie', '1906-07-16', 'challibonei@google.fr');
insert into employee (id, name, birthday, email) values (20, 'Taffy', '1976-05-03', 'tschurckej@eventbrite.com');
insert into employee (id, name, birthday, email) values (21, 'Laureen', '1903-08-22', 'lveryank@noaa.gov');
insert into employee (id, name, birthday, email) values (22, 'Honey', '1981-03-28', 'hmassonl@marriott.com');
insert into employee (id, name, birthday, email) values (23, 'Ernie', '1960-04-28', 'emoylesm@geocities.jp');
insert into employee (id, name, birthday, email) values (24, 'Fancie', '1982-02-27', 'fsalliern@paypal.com');
insert into employee (id, name, birthday, email) values (25, 'Tabby', '1923-05-21', 'twastello@oracle.com');
insert into employee (id, name, birthday, email) values (26, 'Mohandas', '1903-12-15', 'mfuchsp@home.pl');
insert into employee (id, name, birthday, email) values (27, 'Adorne', '1901-01-27', 'abesnardq@cdc.gov');
insert into employee (id, name, birthday, email) values (28, 'Cecily', '2002-05-17', 'csimondr@symantec.com');
insert into employee (id, name, birthday, email) values (29, 'Thelma', '1997-04-02', 'tgibsons@de.vu');
insert into employee (id, name, birthday, email) values (30, 'Margette', '1914-10-29', 'mjollandt@live.com');
insert into employee (id, name, birthday, email) values (31, 'Kit', '1917-03-28', 'kskeldingu@ucsd.edu');
insert into employee (id, name, birthday, email) values (32, 'Sophia', '1991-08-13', 'skarpychevv@hud.gov');
insert into employee (id, name, birthday, email) values (33, 'Petra', '1911-12-03', 'pdugoodw@oaic.gov.au');
insert into employee (id, name, birthday, email) values (34, 'Ken', '1935-01-26', 'ksquierx@independent.co.uk');
insert into employee (id, name, birthday, email) values (35, 'Sigfrid', '1954-12-26', 'smeaseny@discovery.com');
insert into employee (id, name, birthday, email) values (36, 'Jewel', '1995-05-10', 'jcockadayz@uiuc.edu');
insert into employee (id, name, birthday, email) values (37, 'Anne', '1945-04-12', 'avearnals10@bizjournals.com');
insert into employee (id, name, birthday, email) values (38, 'Monika', '1988-02-13', 'mcaccavale11@icio.us');
insert into employee (id, name, birthday, email) values (39, 'Tess', '1976-03-15', 'tfolli12@netlog.com');
insert into employee (id, name, birthday, email) values (40, 'Tiphani', '1963-06-29', 'trook13@mapquest.com');
insert into employee (id, name, birthday, email) values (41, 'Leroi', '1966-06-26', 'lvanoord14@ovh.net');
insert into employee (id, name, birthday, email) values (42, 'Don', '1971-04-30', 'dconnaughton15@house.gov');
insert into employee (id, name, birthday, email) values (43, 'Kristoforo', '1909-08-25', 'kpetrowsky16@bbc.co.uk');
insert into employee (id, name, birthday, email) values (44, 'Reinaldos', '1942-07-07', 'rparkes17@washington.edu');
insert into employee (id, name, birthday, email) values (45, 'Duncan', '1921-12-09', 'dantonomolii18@hibu.com');
insert into employee (id, name, birthday, email) values (46, 'Harley', '1921-12-02', 'hohenecan19@slideshare.net');
insert into employee (id, name, birthday, email) values (47, 'Kettie', '1913-02-01', 'kleggin1a@spotify.com');
insert into employee (id, name, birthday, email) values (48, 'Arlen', '1916-01-16', 'agodridge1b@cdbaby.com');
insert into employee (id, name, birthday, email) values (49, 'Gran', '1976-04-21', 'gheatly1c@nasa.gov');
insert into employee (id, name, birthday, email) values (50, 'Davie', '1940-05-05', 'dpetrozzi1d@myspace.com');

## update işlemi

UPDATE employee
SET name= 'Alpay'
WHERE name LIKE 'K%'
RETURNING *;

UPDATE employee
SET email= 'update@update.com'
WHERE id<5
RETURNING *;

UPDATE employee
SET birthday= '2002-07-23'
WHERE name = 'Alpay'
RETURNING *;

UPDATE employee
SET name= 'Updated'
WHERE id IN(10,20)
RETURNING *;

UPDATE employee
SET name= 'Email'
WHERE email LIKE 'update%'
RETURNING *;

## delete işlemi

DELETE FROM employee
WHERE name = 'Email'
RETURNING *;

DELETE FROM employee
WHERE birthday = '2002-07-23'
RETURNING *;

DELETE FROM employee
WHERE id < 10
RETURNING *;

DELETE FROM employee
WHERE name LIKE 'U%'
RETURNING *;

DELETE FROM employee
WHERE birthday IN ('1919-10-03','1953-03-01')
RETURNING *;
