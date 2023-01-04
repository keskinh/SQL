1 ) country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.
2 ) country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.
3 ) film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.
4 ) film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.



Cevap 1 ) select  * from country where country like 'A%a';

Cevap 2 ) select * from country where country like '_____%n';

Cevap 3 ) SELECT title FROM film WHERE title ILIKE '%t%t%t%t%';

Cevap 4 ) select * from film where title like 'C%' and length >90 and rental_rate =2.99;
