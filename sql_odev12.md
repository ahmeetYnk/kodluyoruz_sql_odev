film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

SELECT COUNT(*) AS ort_uzunluktan_fazla_film_sayisi FROM film
WHERE film.length > (SELECT AVG(film.length) FROM film);

film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?

SELECT COUNT(*) FROM film
WHERE film.rental_rate = (SELECT MAX(film.rental_rate) FROM film);

film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.

SELECT * FROM film
WHERE film.rental_rate = (SELECT MIN(film.rental_rate) FROM film) AND film.replacement_cost = (SELECT MAX(film.replacement_cost) FROM film);

payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.

SELECT customer.customer_id, customer.first_name, customer.last_name, COUNT(payment.payment_id) AS toplam_alisveris_sayisi FROM customer
INNER JOIN payment ON customer.customer_id = payment.customer_id
GROUP BY customer.customer_id
ORDER BY toplam_alisveris_sayisi DESC
LIMIT 1