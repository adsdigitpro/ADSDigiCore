
```docker run --name some-postgres -e POSTGRES_PASSWORD=adspwd -d postgres```

```docker run -p 5050:80  -e "PGADMIN_DEFAULT_EMAIL=user@domain.com"  -e "PGADMIN_DEFAULT_PASSWORD=SuperSecret"   -d dpage/pgadmin4```

```http://localhost:5050/```