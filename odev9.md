1 ) city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

2 ) customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

3 ) customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.



Cevap 1 ) select city, country from city inner join country on (city.country_id=countyr.country_id);

Cevap 2 )  select payment_id. first_name, last_name from payment inner join customer on (payment.customer_id=customer.customer_id);

Cevap 3 )  select rental_id, first_name, last_name from customer inner join rental on (customer.customer_id=rental.customer_id);
