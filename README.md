1. Napisz zapytanie pobierające wszystkich klientów z "Germany"
SELECT * FROM customers WHERE country = "Germany";
2. Napisz zapytanie pobierające wszystkich klientów z "Berlin"
SELECT * FROM customers WHERE city = 'berlin';
3. Napisz zapytanie pobierające wszystkich klientów z miasta "Berlin" i kraju "Germany"
SELECT * FROM customers WHERE city = 'berlin' and country = 'germany';
4. Napisz zapytanie pobierające wszystkich klientów z "Berlin" lub "München" i kraju "Germany"
SELECT * FROM customers WHERE country = 'germany' and (city = 'München' or city = 'berlin');
5. Napisz zapytanie pobierające wszystkich klientów którzy nie są z "Germany" i "USA"
SELECT * FROM customers WHERE not country = 'germany' and not 'country' = 'usa';
6. Napisz zapytanie pobierające wszystkich klientów posortowanych rosnąco po kraju
SELECT * FROM customers ORDER BY country ASC;
7. Napisz zapytanie pobierające wszystkich klientów posortowanych malejąco po kraju
SELECT * FROM customers ORDER BY country DESC;
8. Napisz zapytanie pobierające wszystkich klientów posortowanych malejąco po kraju i rosnąco po "CustomerName"
SELECT * FROM customers ORDER BY country DESC, customer_name ASC;
