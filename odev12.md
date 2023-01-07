
1 ) film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

2 ) film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?

3 ) film tablosunda en düşük rental_rate ve en düşük replacement_cost değerlerine sahip filmleri sıralayınız.

4 ) payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.


Cevap 1 ) select  count (*) from film where length >( select avg(length) from film );

Cevap 2 ) select count(rental_rate) from film  where rental_rate =(select max(rental_rate) from film;

Cevap 3 ) select rental_rate from film where rental_rate =(select min(rental_rate) from film) and replacement_cost = (select min(replacement_cost ) from film);

Cevap 4 ) select customer_id,sum(amount) from payment group by customer-id  order by sum desc limit 5;


