# Postgres

## Mac OS X

### Socket Error

```bash
> psql                                                                                                                                      
psql: could not connect to server: No such file or directory                                                                                          
Is the server running locally and accepting                                                                                                   
connections on Unix domain socket "/tmp/.s.PGSQL.5432"? 
```

If you installed Postgres with Homebrew then this may have happened because you upgraded the database with brew upgrade. To fix run

```bash
brew postgresql-upgrade-database
```

and then restart the database

```bash
brew services start postgresql
```
