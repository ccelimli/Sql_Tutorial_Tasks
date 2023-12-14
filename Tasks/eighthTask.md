#### 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
   CREATE TABLE employee(
        id SERIAL PRIMARY KEY,
        name VARCHAR(50) NOT NULL,
        birthday DATE NOT NULL,
        email VARCHAR(100) NOT NULL
   );
```

#### 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
    insert into author (name, email, birthday) values ('Sully Fakes', 'sfakes0@biblegateway.com', '1993-11-22');
    insert into author (name, email, birthday) values ('Gail Hugle', 'ghugle1@storify.com', '2007-11-05');
    insert into author (name, email, birthday) values ('Godfree Bucke', 'gbucke2@ebay.co.uk', '1993-10-31');
    insert into author (name, email, birthday) values ('Marcelia Rudwell', 'mrudwell3@google.com.br', '1952-12-21');
    insert into author (name, email, birthday) values ('Alisha Rittmeyer', 'arittmeyer4@spiegel.de', '2001-12-08');
    insert into author (name, email, birthday) values ('Mireille Lopez', 'mlopez5@ftc.gov', '1972-07-10');
    insert into author (name, email, birthday) values ('Toddie Brakewell', 'tbrakewell6@psu.edu', '1953-11-07');
    insert into author (name, email, birthday) values ('Sherwin Sandiland', 'ssandiland7@diigo.com', '1994-09-06');
    insert into author (name, email, birthday) values ('Uri Guidini', 'uguidini8@weather.com', '1991-10-26');
    insert into author (name, email, birthday) values ('Guilbert Hulls', 'ghulls9@ft.com', '2020-10-23');
    insert into author (name, email, birthday) values ('Ulrike Kenchington', 'ukenchingtona@earthlink.net', '1998-12-31');
    insert into author (name, email, birthday) values ('Jerrold Law', 'jlawb@canalblog.com', '1968-05-19');
    insert into author (name, email, birthday) values ('Mathew Little', 'mlittlec@github.io', '1972-05-12');
    insert into author (name, email, birthday) values ('Mirabel Cavill', 'mcavilld@loc.gov', '2017-03-07');
    insert into author (name, email, birthday) values ('Hayes Undy', 'hundye@amazon.co.uk', '1956-08-01');
    insert into author (name, email, birthday) values ('Jacobo Flarity', 'jflarityf@photobucket.com', '1966-09-01');
    insert into author (name, email, birthday) values ('Fayth Guiett', 'fguiettg@dagondesign.com', '1985-09-06');
    insert into author (name, email, birthday) values ('Theo Gulston', 'tgulstonh@angelfire.com', '1992-06-27');
    insert into author (name, email, birthday) values ('Cortie Simononsky', 'csimononskyi@comcast.net', '1962-09-09');
    insert into author (name, email, birthday) values ('Cello Andrelli', 'candrellij@baidu.com', '1981-01-23');
    insert into author (name, email, birthday) values ('Robbie Sivill', 'rsivillk@wikipedia.org', '1992-06-28');
    insert into author (name, email, birthday) values ('Kalli MacNelly', 'kmacnellyl@wufoo.com', '2001-12-30');
    insert into author (name, email, birthday) values ('Lockwood Shemilt', 'lshemiltm@flickr.com', '1990-01-16');
    insert into author (name, email, birthday) values ('Ashlin Tighe', 'atighen@geocities.com', '1979-02-11');
    insert into author (name, email, birthday) values ('Hugo Ireland', 'hirelando@xing.com', '2015-11-07');
    insert into author (name, email, birthday) values ('Sasha Kiehnlt', 'skiehnltp@hubpages.com', '1972-03-31');
    insert into author (name, email, birthday) values ('Gwynne Abrashkin', 'gabrashkinq@csmonitor.com', '2012-06-23');
    insert into author (name, email, birthday) values ('Sherie Montilla', 'smontillar@phpbb.com', '1981-11-19');
    insert into author (name, email, birthday) values ('Napoleon Balmadier', 'nbalmadiers@dyndns.org', '1991-01-16');
    insert into author (name, email, birthday) values ('Madalyn Ashelford', 'mashelfordt@wordpress.com', '1965-11-04');
    insert into author (name, email, birthday) values ('Olav Izakof', 'oizakofu@engadget.com', '2008-01-08');
    insert into author (name, email, birthday) values ('Heall Monkton', 'hmonktonv@columbia.edu', '1979-06-09');
    insert into author (name, email, birthday) values ('Susan Loveredge', 'sloveredgew@vimeo.com', '1973-05-19');
    insert into author (name, email, birthday) values ('Gilberte Padilla', 'gpadillax@princeton.edu', '1996-12-02');
    insert into author (name, email, birthday) values ('Vonny Bolsteridge', 'vbolsteridgey@bbc.co.uk', '1980-08-16');
    insert into author (name, email, birthday) values ('Carlen Audiss', 'caudissz@netscape.com', '2011-07-18');
    insert into author (name, email, birthday) values ('Vern Laidlaw', 'vlaidlaw10@umn.edu', '2016-01-28');
    insert into author (name, email, birthday) values ('Bevin Weeds', 'bweeds11@cmu.edu', '1984-03-26');
    insert into author (name, email, birthday) values ('Julissa Hynde', 'jhynde12@nyu.edu', '1996-06-05');
    insert into author (name, email, birthday) values ('Hestia Stut', 'hstut13@independent.co.uk', '2015-08-30');
    insert into author (name, email, birthday) values ('Demetris McGuinley', 'dmcguinley14@flavors.me', '1977-03-17');
    insert into author (name, email, birthday) values ('Jaynell Draycott', 'jdraycott15@reuters.com', '1993-03-01');
    insert into author (name, email, birthday) values ('Kevina Comberbach', 'kcomberbach16@squarespace.com', '1950-01-05');
    insert into author (name, email, birthday) values ('Gib McGenis', 'gmcgenis17@craigslist.org', '2010-02-28');
    insert into author (name, email, birthday) values ('Bruce Fearneley', 'bfearneley18@github.io', '1965-01-15');
    insert into author (name, email, birthday) values ('Janna Loyley', 'jloyley19@gmpg.org', '1996-12-27');
    insert into author (name, email, birthday) values ('Dorene Southam', 'dsoutham1a@europa.eu', '1997-06-26');
    insert into author (name, email, birthday) values ('Jerad Gibbieson', 'jgibbieson1b@yahoo.com', '1970-12-07');
    insert into author (name, email, birthday) values ('Rayna Keam', 'rkeam1c@globo.com', '1952-01-17');
    insert into author (name, email, birthday) values ('Marilin Cornillot', 'mcornillot1d@weebly.com', '1991-03-18');
```

#### 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
   -1 numaralı ID'ye sahip kullanıcı
        UPDATE author
            SET name = 'Deneme Kullanici',
                birthday = '2000-11-06',
                email = 'deneme@info.com'
            WHERE id=1;
       RETURNING *;
       
   - Name sütunu 'J' harfi ile başlayan kullanıcılar -
        UPDATE author
            SET name = 'XXXX',
                birthday = '1900-01-01',
                email = 'XXXX'
            WHERE name ILIKE 'J%'  
       RETURNING *;
   
   - Çift sayı ID değerine sahip kullanıcılar -
        UPDATE author
            SET name = 'XXXX',
                birthday = '1900-01-01',
                email = 'XXXX'
            WHERE id%2=0  
       RETURNING *;
       
   - 13,15,17 ID numarasına sahip kullanıcılar -
        UPDATE author
            SET name = 'XXXX',
                birthday = '1900-01-01',
                email = 'XXXX'
            WHERE id IN(13,15,17)  
       RETURNING *;
       
   -Email sütununda deneme kelimesi bulunan
        UPDATE author
            SET name = 'XXXX',
                birthday = '1900-01-01',
                email = 'XXXX'
            WHERE email LIKE '%deneme%' 
       RETURNING *;
```

#### 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
   - 1 numaralı ID'ye sahip kullanıcı -
       DELETE FROM author
            WHERE id=1;
       RETURNING *;
       
   - Name sütunu 'J' harfi ile başlayan kullanıcılar -
        DELETE FROM author
            WHERE name ILIKE 'J%'  
        RETURNING *;
   
   - Çift sayı ID değerine sahip kullanıcılar-
        DELETE FROM author
            WHERE id%2=0  
        RETURNING *;
       
   - 13,15,17 ID numarasına sahip kullanıcılar -
        DELETE FROM author
            WHERE id IN(13,15,17)  
        RETURNING *;
       
   - Email sütununda deneme kelimesi bulunan -
        DELETE FROM author
            WHERE email LIKE '%deneme%' 
        RETURNING *;
```