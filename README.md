# Project-17-SQL-Commands-PostgreSQL
These are assignments given in Patika Java Intermediate course.


## Tasks

-  Create a table named employee in your test database with the following columns:

    * id (INTEGER)
    * name (VARCHAR(50))
    * birthday (DATE)
    * email (VARCHAR(100))

Using the 'Mockaroo' service, let's add 50 records to the employee table.

- Perform 5 UPDATE operations that update other columns based on each of the columns.

- Perform 5 DELETE operations that delete the relevant row based on each of the columns.




## Queries

```

-- TASK1 
CREATE TABLE employee(
    id INTEGER NOT NULL,
    name VARCHAR(50) NOT NULL,
    birthday DATE NOT NULL,
    email VARCHAR(100) NOT NULL
);

-- TASK2
insert into employee (id, name, birthday, email) values (1, 'Obie Arden', '1999-07-23', 'oarden0@dell.com');
insert into employee (id, name, birthday, email) values (2, 'Tiebold Nicolson', '1973-03-07', 'tnicolson1@digg.com');
insert into employee (id, name, birthday, email) values (3, 'Francis Kinnier', '1987-07-26', 'fkinnier2@deliciousdays.com');
insert into employee (id, name, birthday, email) values (4, 'Forester Senter', '1985-06-01', 'fsenter3@senate.gov');
insert into employee (id, name, birthday, email) values (5, 'Verney Lumox', '1972-06-02', 'vlumox4@tinyurl.com');
insert into employee (id, name, birthday, email) values (6, 'Mackenzie Pietrzak', '2003-05-23', 'mpietrzak5@istockphoto.com');
insert into employee (id, name, birthday, email) values (7, 'Rebecca Merton', '1984-10-06', 'rmerton6@php.net');
insert into employee (id, name, birthday, email) values (8, 'Lucias Sayward', '2005-09-17', 'lsayward7@imageshack.us');
insert into employee (id, name, birthday, email) values (9, 'Ludvig Josephoff', '1995-04-01', 'ljosephoff8@typepad.com');
insert into employee (id, name, birthday, email) values (10, 'Terza Risdall', '1991-04-12', 'trisdall9@posterous.com');
insert into employee (id, name, birthday, email) values (11, 'Kessia Gilphillan', '1995-07-28', 'kgilphillana@hc360.com');
insert into employee (id, name, birthday, email) values (12, 'Sonnie Abys', '2013-09-19', 'sabysb@businessinsider.com');
insert into employee (id, name, birthday, email) values (13, 'Petunia Bumphries', '2021-11-16', 'pbumphriesc@jigsy.com');
insert into employee (id, name, birthday, email) values (14, 'Shanie Radford', '1977-02-27', 'sradfordd@boston.com');
insert into employee (id, name, birthday, email) values (15, 'Zitella Loughton', '2002-07-11', 'zloughtone@360.cn');
insert into employee (id, name, birthday, email) values (16, 'Fallon Dovidian', '2010-04-20', 'fdovidianf@state.tx.us');
insert into employee (id, name, birthday, email) values (17, 'Augy Beltzner', '1994-05-03', 'abeltznerg@ovh.net');
insert into employee (id, name, birthday, email) values (18, 'Roxie Venney', '2003-12-03', 'rvenneyh@home.pl');
insert into employee (id, name, birthday, email) values (19, 'Tuckie Tribell', '2014-12-09', 'ttribelli@washington.edu');
insert into employee (id, name, birthday, email) values (20, 'Boy Fealey', '2017-12-12', 'bfealeyj@icio.us');
insert into employee (id, name, birthday, email) values (21, 'Aksel Paddock', '1975-05-13', 'apaddockk@spiegel.de');
insert into employee (id, name, birthday, email) values (22, 'Jessica Petre', '2007-11-18', 'jpetrel@sbwire.com');
insert into employee (id, name, birthday, email) values (23, 'Griffy Jaksic', '1976-05-05', 'gjaksicm@acquirethisname.com');
insert into employee (id, name, birthday, email) values (24, 'Dannye Campey', '1981-02-15', 'dcampeyn@booking.com');
insert into employee (id, name, birthday, email) values (25, 'Rhetta Blacktin', '2014-08-17', 'rblacktino@typepad.com');
insert into employee (id, name, birthday, email) values (26, 'Edwina Barlie', '2011-02-19', 'ebarliep@pinterest.com');
insert into employee (id, name, birthday, email) values (27, 'Mirna Minchenton', '2002-12-26', 'mminchentonq@vimeo.com');
insert into employee (id, name, birthday, email) values (28, 'Maighdiln Tams', '2019-01-14', 'mtamsr@gravatar.com');
insert into employee (id, name, birthday, email) values (29, 'Piggy Wisham', '2017-08-24', 'pwishams@google.co.jp');
insert into employee (id, name, birthday, email) values (30, 'Tabby Carlsen', '1981-09-05', 'tcarlsent@clickbank.net');
insert into employee (id, name, birthday, email) values (31, 'Marcia Daniel', '2003-02-04', 'mdanielu@google.nl');
insert into employee (id, name, birthday, email) values (32, 'Karena Gallamore', '1994-09-03', 'kgallamorev@google.es');
insert into employee (id, name, birthday, email) values (33, 'Brew Schelle', '2013-04-28', 'bschellew@nasa.gov');
insert into employee (id, name, birthday, email) values (34, 'Belinda Powton', '1994-06-27', 'bpowtonx@hc360.com');
insert into employee (id, name, birthday, email) values (35, 'Gayler Swindley', '1979-05-13', 'gswindleyy@cyberchimps.com');
insert into employee (id, name, birthday, email) values (36, 'Gale Lamblot', '1981-03-13', 'glamblotz@yale.edu');
insert into employee (id, name, birthday, email) values (37, 'Bogey Mooring', '2020-02-19', 'bmooring10@blogspot.com');
insert into employee (id, name, birthday, email) values (38, 'Marieann Liddard', '1980-01-31', 'mliddard11@histats.com');
insert into employee (id, name, birthday, email) values (39, 'Mick Downe', '1993-05-31', 'mdowne12@utexas.edu');
insert into employee (id, name, birthday, email) values (40, 'Toni MacRury', '2013-01-15', 'tmacrury13@mtv.com');
insert into employee (id, name, birthday, email) values (41, 'Brig Danell', '1985-05-10', 'bdanell14@unicef.org');
insert into employee (id, name, birthday, email) values (42, 'Jessi Grimsdith', '1990-03-29', 'jgrimsdith15@yellowpages.com');
insert into employee (id, name, birthday, email) values (43, 'Vlad Kembley', '1982-05-20', 'vkembley16@elpais.com');
insert into employee (id, name, birthday, email) values (44, 'Kissee Trewman', '1989-05-21', 'ktrewman17@senate.gov');
insert into employee (id, name, birthday, email) values (45, 'Gaynor Avraam', '1989-04-28', 'gavraam18@sourceforge.net');
insert into employee (id, name, birthday, email) values (46, 'Alf Busswell', '1996-04-06', 'abusswell19@homestead.com');
insert into employee (id, name, birthday, email) values (47, 'Batsheva Philson', '2009-08-17', 'bphilson1a@howstuffworks.com');
insert into employee (id, name, birthday, email) values (48, 'Ursuline Dowry', '1982-12-09', 'udowry1b@samsung.com');
insert into employee (id, name, birthday, email) values (49, 'Ralph Brereton', '2011-02-06', 'rbrereton1c@answers.com');
insert into employee (id, name, birthday, email) values (50, 'Isobel Gilli', '1994-02-19', 'igilli1d@baidu.com');


SELECT * FROM employee;

-- TASK3
UPDATE employee
SET name = 'update1',
    birthday = '1999-07-23',
    email = 'update1@mail.com'
WHERE id BETWEEN 1 AND 5;

SELECT * FROM employee;

-- TASK4
DELETE FROM employee
WHERE id BETWEEN 10 AND 14;

SELECT * FROM employee;


```
