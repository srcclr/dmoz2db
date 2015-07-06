# Update DMOZ categories and domains categories

Forked from [dmo2db](https://github.com/JoKnopp/dmoz2db).

# Installation

- Make sure you have pip and sqlalchemy 0.6.5 or higher installed

- `git@github.com:Securonauts/dmoz2db.git`

- Download structure.rdf.u8 from [DMOZ](http://rdf.dmoz.org/rdf/)

- Download content.rdf.u8 from [DMOZ](http://rdf.dmoz.org/rdf/)

- Copy `db.sample.conf` to `db.conf` and update config

```bash
python dmoz2db.py --keep-db -s structure.rdf.u8 -c content.rdf.u8
```

- `psql DATABASE_NAME < src/lib/normalize.sql`
