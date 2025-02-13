test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
id SERIAL PRIMARY KEY,
name VARCHAR(50) NOT NULL,
birthday DATE,
email VARCHAR(50)
);

Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (name, birthday, email) values ('Jedd', '1942-07-04', 'jschimpke0@illinois.edu');
insert into employee (name, birthday, email) values ('Ollie', '1983-12-22', 'odedomenicis1@list-manage.com');
insert into employee (name, birthday, email) values ('Kyrstin', '1963-07-07', 'kiggalden2@tinyurl.com');
insert into employee (name, birthday, email) values ('Millie', '1995-09-20', 'mcoda3@washingtonpost.com');
insert into employee (name, birthday, email) values ('Bendite', '1959-02-11', 'bheigold4@si.edu');
insert into employee (name, birthday, email) values ('Jefferson', '1974-03-17', 'jyushmanov5@mac.com');
insert into employee (name, birthday, email) values ('Fawne', '1915-01-12', 'fjack6@youtu.be');
insert into employee (name, birthday, email) values ('Reinaldos', '1995-06-07', 'rdumingos7@people.com.cn');
insert into employee (name, birthday, email) values ('Freddy', '1905-11-26', 'fsavin8@soup.io');
insert into employee (name, birthday, email) values ('Misty', '1904-01-11', 'mpriver9@google.ru');
insert into employee (name, birthday, email) values ('Val', '1965-03-20', 'vquarringtona@hatena.ne.jp');
insert into employee (name, birthday, email) values ('Maggee', '1902-10-26', 'mfulbrookb@t.co');
insert into employee (name, birthday, email) values ('Stormie', '1984-03-25', 'scookneyc@earthlink.net');
insert into employee (name, birthday, email) values ('Mickie', '1998-01-26', 'mvalentind@google.com.au');
insert into employee (name, birthday, email) values ('Abbey', '1965-10-18', 'amulmuraye@springer.com');
insert into employee (name, birthday, email) values ('Cesare', '1984-03-12', 'cbricknellf@infoseek.co.jp');
insert into employee (name, birthday, email) values ('Zelig', '1935-12-14', 'ztessierg@xing.com');
insert into employee (name, birthday, email) values ('Filide', '1909-01-13', 'fgannonh@github.io');
insert into employee (name, birthday, email) values ('Sonnie', '1985-01-25', 'sbickardikei@networksolutions.com');
insert into employee (name, birthday, email) values ('Leela', '1986-09-19', 'lgarnhamj@youtu.be');
insert into employee (name, birthday, email) values ('Gerik', '1942-12-02', 'gdeeslyk@nydailynews.com');
insert into employee (name, birthday, email) values ('Cassandra', '1947-11-14', 'cstovesl@illinois.edu');
insert into employee (name, birthday, email) values ('Mureil', '1997-02-04', 'mbrownhillm@posterous.com');
insert into employee (name, birthday, email) values ('Anatol', '1932-06-01', 'awalesan@google.com');
insert into employee (name, birthday, email) values ('Irina', '1966-12-03', 'ijelfso@shutterfly.com');
insert into employee (name, birthday, email) values ('Carissa', '1928-05-15', 'cploverp@slate.com');
insert into employee (name, birthday, email) values ('Gisela', '1927-06-15', 'gtidbaldq@skype.com');
insert into employee (name, birthday, email) values ('Kelli', '1971-04-24', 'kpyfordr@disqus.com');
insert into employee (name, birthday, email) values ('Genia', '1940-09-10', 'gclifts@slideshare.net');
insert into employee (name, birthday, email) values ('Adda', '1985-03-13', 'agoldhawkt@furl.net');
insert into employee (name, birthday, email) values ('Joane', '1966-03-14', 'jcleryu@ted.com');
insert into employee (name, birthday, email) values ('Winna', '1967-05-19', 'wbouttonv@netlog.com');
insert into employee (name, birthday, email) values ('Shanie', '1939-10-09', 'swindibankw@arizona.edu');
insert into employee (name, birthday, email) values ('Talyah', '1947-01-20', 'tcardellox@ow.ly');
insert into employee (name, birthday, email) values ('Annmaria', '1936-02-29', 'arivey@thetimes.co.uk');
insert into employee (name, birthday, email) values ('Suzie', '1972-04-23', 'sgippsz@livejournal.com');
insert into employee (name, birthday, email) values ('Sigvard', '1975-03-05', 'ssaer10@cam.ac.uk');
insert into employee (name, birthday, email) values ('Lona', '1930-12-26', 'lwoolward11@walmart.com');
insert into employee (name, birthday, email) values ('Shayne', '1902-02-01', 'scaldeyroux12@csmonitor.com');
insert into employee (name, birthday, email) values ('Reynard', '1971-05-30', 'rgunney13@mac.com');
insert into employee (name, birthday, email) values ('Karie', '1901-07-17', 'kbarstock14@elpais.com');
insert into employee (name, birthday, email) values ('Krista', '1971-12-17', 'keadon15@sogou.com');
insert into employee (name, birthday, email) values ('Vic', '1983-04-07', 'vmoraleda16@statcounter.com');
insert into employee (name, birthday, email) values ('Josias', '1954-10-05', 'jmathou17@a8.net');
insert into employee (name, birthday, email) values ('Berrie', '1902-10-10', 'blagden18@independent.co.uk');
insert into employee (name, birthday, email) values ('Elizabeth', '1948-03-01', 'ebradneck19@twitpic.com');
insert into employee (name, birthday, email) values ('Wes', '1920-03-10', 'wbris1a@auda.org.au');
insert into employee (name, birthday, email) values ('Raul', '1986-09-27', 'rmanthroppe1b@disqus.com');
insert into employee (name, birthday, email) values ('Ofelia', '1946-05-08', 'ogoldsbrough1c@toplist.cz');
insert into employee (name, birthday, email) values ('Kriste', '1946-01-05', 'ktudbald1d@princeton.edu');


Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name = 'Fred',
birthday = '1999-05-03',
email = 'Fred@hotmail.com'
WHERE id = 1;

UPDATE employee
SET name = 'Tadic',
birthday = '1985-13-15',
email = 'tadic@gmail.com'
WHERE name = 'Raul'

UPDATE employee
SET name = 'Talisca',
birthday = '1989-08-25',
email = 'talisca@gmail.com'
WHERE id = 10;

UPDATE employee
SET name = 'En-Nesyri',
birthday = '1992-06-22',
email = 'en-nesyri@gmail.com'
WHERE id = 50;

UPDATE employee
SET name = 'Szymanski',
birthday = '1996-07-12',
email = 'szymanski@gmail.com'
WHERE name = 'Ollie';

Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE name = 'Bendite';

DELETE FROM employee
WHERE id = 34;

DELETE FROM employee
WHERE name LIKE 'Eliza%';

DELETE FROM employee
WHERE email LIKE '%earthlink%';

DELETE FROM employee
WHERE id = 45;




