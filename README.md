```sql
1. SELECT rating, COUNT(*) FROM film GROUP BY rating;
```
```sql
2. SELECT replacement_cost, COUNT(*) FROM film GROUP BY replacement_cost HAVING COUNT(*) > 50;
```
```sql
3. SELECT store_id, COUNT(*) FROM customer GROUP BY store_id;
```
```sql
4. SELECT country_id, COUNT(*) count FROM city GROUP BY country_id ORDER BY count DESC LIMIT 1;
```
