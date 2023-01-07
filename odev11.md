1 ) actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.

2 ) actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.

3 ) actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.

4 )İlk 3 sorguyu tekrar eden veriler için de yapalım.



Cevap 1) 
(select first_name from actor order by firs_name)
union
(select first_name from customer order by first_name)


Cevap 2 )
(select first_name from actor order by first_name)
intersect
(select first_name from customer order by first_name)


Cevap 3 )
(select first_name from actor order by first_name)
except
(select first_name from customer order by first_name)


Cevap 4 ) //tekrar edenler için//
(select first_name from actor order by firs_name)
union all
(select first_name from customer order by first_name)


(select first_name from actor order by first_name)
intersect
(select first_name from customer order by first_name)


(select first_name from actor order by first_name)
except all
(select first_name from customer order by first_name)

