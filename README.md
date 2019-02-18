# Seleccionar-resultados-desde-una-fecha-X-MySQL

```sql
where yourdate_column > DATE_SUB(now(), INTERVAL 6 MONTH)
```
Source: https://dev.mysql.com/doc/refman/8.0/en/date-and-time-functions.html#function_datediff
