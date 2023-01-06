1 ) test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

2 ) Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

3 ) Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

4 ) Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.



Cevap 1) create table employee (id integer, Name varchar(50), birthday date, email varchar(100));


Cevap 2) 
insert into employee (id, name, email, birthday) values (1, 'Merci', 'mleemanss@github.com', '1966-12-12');

insert into employee (id, name, email, birthday) values (2, 'Arvin', 'abettst@dot.gov', '1902-06-21');

insert into employee (id, name, email, birthday) values (3, 'Ade', 'ajohnsonu@arstechnica.com', '1984-09-10');

insert into employee (id, name, email, birthday) values (4, 'Willy', null, '1906-02-15');

insert into employee (id, name, email, birthday) values (5, 'Colline', 'ccosinsw@fc2.com', '1982-03-04');

insert into employee (id, name, email, birthday) values (6, 'Son', 'sstclairx@cnn.com', '1927-05-29');

insert into employee (id, name, email, birthday) values (7, 'Neely', 'njozwiaky@photobucket.com', null);

insert into employee (id, name, email, birthday) values (8, 'Afton', 'abasilottaz@fc2.com', '1981-07-21');

insert into employee (id, name, email, birthday) values (9, 'Darbie', 'dhillatt10@archive.org', '1926-02-16');

insert into employee (id, name, email, birthday) values (10, 'Briggs', 'bphilp11@wikia.com', '1926-08-21');

insert into employee (id, name, email, birthday) values (11, 'Kalinda', 'kkesby12@guardian.co.uk', '1973-06-07');

insert into employee (id, name, email, birthday) values (12, 'Johannah', 'jkorn13@cnn.com', null);

insert into employee (id, name, email, birthday) values (13, 'Joey', 'jhindge14@gnu.org', '1925-02-19');

insert into employee (id, name, email, birthday) values (14, 'Deni', 'dhundey15@domainmarket.com', null);

insert into employee (id, name, email, birthday) values (15, 'Melva', 'mhalden16@sciencedirect.com', '1904-03-04');

insert into employee (id, name, email, birthday) values (16, 'Vidovic', 'vblade17@altervista.org', '1962-01-29');

insert into employee (id, name, email, birthday) values (17, 'Gabriellia', null, '1938-09-30');

insert into employee (id, name, email, birthday) values (18, 'Lusa', 'lbelli19@mozilla.com', '2013-03-22');

insert into employee (id, name, email, birthday) values (19, 'Obie', 'obouts1a@mit.edu', '1913-12-07');

insert into employee (id, name, email, birthday) values (20, 'Arie', 'apeoples1b@mit.edu', null);

insert into employee (id, name, email, birthday) values (21, 'Dacie', 'dvear1c@tinyurl.com', '1951-10-22');

insert into employee (id, name, email, birthday) values (22, 'Ruby', 'rhodges1d@google.fr', null);

insert into employee (id, name, email, birthday) values (23, 'Thedric', 'tderrett0@apple.com', '1997-07-30');

insert into employee (id, name, email, birthday) values (24, 'Chelsae', null, '1936-10-25');

insert into employee (id, name, email, birthday) values (25, 'Klaus', null, '1915-10-21');

insert into employee (id, name, email, birthday) values (26, 'Leela', 'ledmead3@europa.eu', '1960-03-22');

insert into employee (id, name, email, birthday) values (27, 'Joaquin', 'jcampsall4@webeden.co.uk', '1978-12-16');

insert into employee (id, name, email, birthday) values (28, 'Annmaria', 'aduesbury5@indiatimes.com', '1949-08-09');

insert into employee (id, name, email, birthday) values (29, 'Janeva', 'jjee6@vk.com', '1987-11-02');

insert into employee (id, name, email, birthday) values (30, 'Taffy', 'tmcgragh7@mlb.com', null);

insert into employee (id, name, email, birthday) values (31, 'Lindsy', 'lparlor8@wired.com', '2006-03-3
1');
insert into employee (id, name, email, birthday) values (32, 'Reuben', 'rjordine9@163.com', '1962-11-14');

insert into employee (id, name, email, birthday) values (33, 'Oneida', 'ocrumlya@zdnet.com', '2005-06-18');

insert into employee (id, name, email, birthday) values (34, 'Arley', 'aofinanb@sohu.com', null);

insert into employee (id, name, email, birthday) values (35, 'Jesselyn', 'jfyfec@tamu.edu', null);

insert into employee (id, name, email, birthday) values (36, 'Gabrila', 'gmelonbyd@clickbank.net', '1927-12-08');

insert into employee (id, name, email, birthday) values (37, 'Don', 'dspure@alexa.com', '2011-09-01');

insert into employee (id, name, email, birthday) values (38, 'Franz', 'fcracknellf@engadget.com', '1961-06-28');

insert into employee (id, name, email, birthday) values (39, 'Dexter', 'dbougheyg@java.com', '1951-11-30');

insert into employee (id, name, email, birthday) values (40, 'Isadore', 'iblunsdenh@sakura.ne.jp', '1975-06-05');

insert into employee (id, name, email, birthday) values (41, 'Lewie', 'lcrafteri@berkeley.edu', '1930-07-17');

insert into employee (id, name, email, birthday) values (42, 'Morganne', 'mabrahamovitzj@wunderground.com', '2018-08-28');

insert into employee (id, name, email, birthday) values (43, 'Alicia', 'atownsendk@cornell.edu', '1984-11-15');

insert into employee (id, name, email, birthday) values (44, 'Kat', 'ktrevnal@biblegateway.com', '2007-03-30');

insert into employee (id, name, email, birthday) values (45, 'Duff', 'dgermanm@yellowbook.com', '1912-05-14');

insert into employee (id, name, email, birthday) values (46, 'Maddi', 'mswanwickn@a8.net', null);

insert into employee (id, name, email, birthday) values (47, 'Claudetta', 'cfidellio@sogou.com', '1987-12-12');

insert into employee (id, name, email, birthday) values (48, 'Stan', 'sjurekp@telegraph.co.uk', null);

insert into employee (id, name, email, birthday) values (49, 'Georgeanne', 'ggoldenq@unesco.org', '1917-03-03');

insert into employee (id, name, email, birthday) values (50, 'Francklin', null, '2004-12-09');


Cevap 3) 
update employee set name='Maddi' where id=3;

update employee set email='cfidellio@sogou.com' where name='Stan';

update employee set birthday='2007-03-30' where id=5;

update employee set email='dbougheyg@java.com' where birthday='1917-03-03';

update employee set name='Kat' where id=13;




Cevap 4)
delete from employee where name='Franz';

delete from employee where id=44;

delete from employee where email='aduesbury5@indiatimes.com';

delete from employee where name='Morganne';

delete from employee where birthday='2005-06-18';
