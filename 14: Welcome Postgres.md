# [PostgreSQL](https://www.postgresql.org/)

> # PostgreSQL: The World's Most Advanced Open Source Relational Database
>
> [Download ](https://www.postgresql.org/download/)

# Installation

```bash
$ sudo pacman -S yay postgresql # Dependencies installation
$ sudo -u postgres -i # Login as PostgreSQL
$ initdb --locale $LANG -E UTF8 -D '/var/lib/postgres/data/'
$ exit
$ sudo systemctl enable --now postgresql # Enabling the service
$ sudo systemctl status postgresql # To check if it is 'Active'
$ # Setting the password
$ psql -U postgres
postgres=# \password # '\password' is not a comment...
```

# PGAdmin

Currently, I'm having problems with installing PGAdmin 4 in my machine. So, There are some alternatives given below:

[DataGrip - JetBrains (Paid)](https://www.jetbrains.com/datagrip/)

[DBeaver - Community Edition (Free)](https://dbeaver.io/download/)

[VSCode SQL Tools Extension](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)

