Downloaded:

- https://homepages.cwi.nl/~boncz/job/imdb.tgz on 2024-03-05.
- https://www-db.in.tum.de/~leis/qo/job.tgz on 2024-03-05.

Split with:
- `split -b 10m "imdb.tgz" "imdb.tgz.part-"`

Join with:
- `cat imdb.tgz.part* > imdb.tgz`

