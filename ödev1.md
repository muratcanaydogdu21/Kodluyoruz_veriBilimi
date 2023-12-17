SELECT title , description from film;
SELECT length from film
where length >60 and  length> 75;
select * from film WHERE rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99);
SELECT * FROM customer WHERE first_name = 'Mary'; =&gt; Smith;
SELECT * FROM film WHERE length &gt; 50 AND (rental_rate &lt;&gt; 2.99 OR rental_rate &lt;&gt; 4.99);
