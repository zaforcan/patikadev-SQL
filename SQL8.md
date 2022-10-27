 # patikadev-SQL Ödev-8
 
 
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(id INT, name VARCHAR(50), birthday DATE, email VARCHAR(100));
```
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, first_name, last_name, birthday, email) values (1, 'Crista', 'Durward', '1975-02-20', 'cdurward0@adobe.com');
insert into employee (id, first_name, last_name, birthday, email) values (2, 'Darda', 'Carnock', '1948-06-26', 'dcarnock1@zimbio.com');
insert into employee (id, first_name, last_name, birthday, email) values (3, 'Land', 'Lupson', '1912-11-19', 'llupson2@google.com');
insert into employee (id, first_name, last_name, birthday, email) values (4, 'Elnore', 'Staresmeare', '1954-02-27', 'estaresmeare3@imgur.com');
insert into employee (id, first_name, last_name, birthday, email) values (5, 'Crichton', 'Hawlgarth', '1903-09-29', 'chawlgarth4@pcworld.com');
insert into employee (id, first_name, last_name, birthday, email) values (6, 'Bink', 'McGoldrick', '1984-06-18', 'bmcgoldrick5@go.com');
insert into employee (id, first_name, last_name, birthday, email) values (7, 'Gwenette', 'Brokenshaw', '1939-08-30', 'gbrokenshaw6@privacy.gov.au');
insert into employee (id, first_name, last_name, birthday, email) values (8, 'Clarice', 'Lock', '1941-04-07', 'clock7@bing.com');
insert into employee (id, first_name, last_name, birthday, email) values (9, 'Babette', 'Ockland', '1977-08-27', 'bockland8@washingtonpost.com');
insert into employee (id, first_name, last_name, birthday, email) values (10, 'Halimeda', 'Berthomier', '1916-07-24', 'hberthomier9@i2i.jp');
insert into employee (id, first_name, last_name, birthday, email) values (11, 'Camel', 'Bail', '1937-09-22', 'cbaila@illinois.edu');
insert into employee (id, first_name, last_name, birthday, email) values (12, 'Maurise', 'Murfill', '1926-07-02', 'mmurfillb@eepurl.com');
insert into employee (id, first_name, last_name, birthday, email) values (13, 'Victoria', 'Joysey', '1982-10-22', 'vjoyseyc@reuters.com');
insert into employee (id, first_name, last_name, birthday, email) values (14, 'Eydie', 'Mattack', '1989-10-17', 'emattackd@chron.com');
insert into employee (id, first_name, last_name, birthday, email) values (15, 'Faun', 'Sprowles', '1928-10-12', 'fsprowlese@360.cn');
insert into employee (id, first_name, last_name, birthday, email) values (16, 'Christoffer', 'Coase', '1907-08-12', 'ccoasef@bing.com');
insert into employee (id, first_name, last_name, birthday, email) values (17, 'Glennis', 'Prue', '1972-06-06', 'gprueg@studiopress.com');
insert into employee (id, first_name, last_name, birthday, email) values (18, 'Verine', 'Eskriett', '1999-11-14', 'veskrietth@ustream.tv');
insert into employee (id, first_name, last_name, birthday, email) values (19, 'Alessandra', 'Cush', '1979-08-04', 'acushi@wikimedia.org');
insert into employee (id, first_name, last_name, birthday, email) values (20, 'Rafael', 'Origin', '1932-06-15', 'roriginj@jimdo.com');
insert into employee (id, first_name, last_name, birthday, email) values (21, 'Ester', 'Forsyth', '1947-01-19', 'eforsythk@baidu.com');
insert into employee (id, first_name, last_name, birthday, email) values (22, 'Ilene', 'Jerzak', '1992-11-26', 'ijerzakl@usgs.gov');
insert into employee (id, first_name, last_name, birthday, email) values (23, 'Susanne', 'Barends', '1920-06-13', 'sbarendsm@un.org');
insert into employee (id, first_name, last_name, birthday, email) values (24, 'Egon', 'Kidgell', '1905-05-02', 'ekidgelln@europa.eu');
insert into employee (id, first_name, last_name, birthday, email) values (25, 'Prentiss', 'Benazet', '1978-02-11', 'pbenazeto@telegraph.co.uk');
insert into employee (id, first_name, last_name, birthday, email) values (26, 'Abigale', 'Yanshin', '1913-06-15', 'ayanshinp@mozilla.org');
insert into employee (id, first_name, last_name, birthday, email) values (27, 'Gracia', 'Baigent', '1902-12-23', 'gbaigentq@sitemeter.com');
insert into employee (id, first_name, last_name, birthday, email) values (28, 'Tressa', 'Gheorghie', '1995-04-19', 'tgheorghier@virginia.edu');
insert into employee (id, first_name, last_name, birthday, email) values (29, 'Maddie', 'Francescuzzi', '1907-06-14', 'mfrancescuzzis@cdbaby.com');
insert into employee (id, first_name, last_name, birthday, email) values (30, 'Tod', 'Wherton', '1960-04-18', 'twhertont@tmall.com');
insert into employee (id, first_name, last_name, birthday, email) values (31, 'Ambrosi', 'Maccraw', '1968-10-15', 'amaccrawu@google.nl');
insert into employee (id, first_name, last_name, birthday, email) values (32, 'Claudio', 'Andreutti', '1971-09-02', 'candreuttiv@github.com');
insert into employee (id, first_name, last_name, birthday, email) values (33, 'Urbanus', 'Hensmans', '1980-06-02', 'uhensmansw@microsoft.com');
insert into employee (id, first_name, last_name, birthday, email) values (34, 'Uri', 'Arnault', '1964-12-07', 'uarnaultx@cbslocal.com');
insert into employee (id, first_name, last_name, birthday, email) values (35, 'Haslett', 'Aprahamian', '1961-08-11', 'haprahamiany@cdbaby.com');
insert into employee (id, first_name, last_name, birthday, email) values (36, 'Dulciana', 'McCandie', '1964-07-12', 'dmccandiez@mediafire.com');
insert into employee (id, first_name, last_name, birthday, email) values (37, 'Ryun', 'Rosenfarb', '1959-12-13', 'rrosenfarb10@yahoo.com');
insert into employee (id, first_name, last_name, birthday, email) values (38, 'Claudina', 'Arnoll', '1995-12-21', 'carnoll11@biblegateway.com');
insert into employee (id, first_name, last_name, birthday, email) values (39, 'Tallia', 'Castrillo', '1951-04-07', 'tcastrillo12@loc.gov');
insert into employee (id, first_name, last_name, birthday, email) values (40, 'Geralda', 'Pinock', '1926-03-06', 'gpinock13@weibo.com');
insert into employee (id, first_name, last_name, birthday, email) values (41, 'Evangelina', 'Foulcher', '1935-03-02', 'efoulcher14@sciencedirect.com');
insert into employee (id, first_name, last_name, birthday, email) values (42, 'Leelah', 'Quenby', '1967-07-06', 'lquenby15@elpais.com');
insert into employee (id, first_name, last_name, birthday, email) values (43, 'Roddy', 'Patten', '1904-04-28', 'rpatten16@fema.gov');
insert into employee (id, first_name, last_name, birthday, email) values (44, 'Mata', 'Rawcliff', '1905-04-04', 'mrawcliff17@aol.com');
insert into employee (id, first_name, last_name, birthday, email) values (45, 'Sigvard', 'Hordle', '1973-01-25', 'shordle18@unblog.fr');
insert into employee (id, first_name, last_name, birthday, email) values (46, 'Emmanuel', 'Klimshuk', '1917-03-27', 'eklimshuk19@china.com.cn');
insert into employee (id, first_name, last_name, birthday, email) values (47, 'Rosamund', 'Muskett', '1934-01-05', 'rmuskett1a@google.es');
insert into employee (id, first_name, last_name, birthday, email) values (48, 'Brigit', 'Kibbye', '1972-05-24', 'bkibbye1b@tinypic.com');
insert into employee (id, first_name, last_name, birthday, email) values (49, 'Farr', 'Plaister', '1972-01-19', 'fplaister1c@oaic.gov.au');
insert into employee (id, first_name, last_name, birthday, email) values (50, 'Goober', 'Beininck', '1918-09-15', 'gbeininck1d@admin.ch');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee SET name = 'değiştirildi' WHERE id IN (2,9,12,15,21);
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee WHERE id IN (2,9,12,15,21);
```
