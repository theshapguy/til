# Kill Database Sessions

The following snippet kills all connected database sessions except the current connected connection.

```sql
SELECT
  pg_terminate_backend(pid)
FROM
  pg_stat_activity
WHERE
  pid <> pg_backend_pid()
  AND datname = 'database_name';
```
