# Openelections Results WI

Wisconsin election results. Currently only including raw files baked from the openelections-core repo.

To produce the raw files:
1. Clone [openelections-core](https://github.com/openelections/openelections-core#getting-started-as-a-developer).
2. Follow that repo's instructions for [bootstrapping your environment](https://github.com/openelections/openelections-core#getting-started-as-a-developer).
3. `openelex fetch --state wi`
4. `openelex load.run --state wi`
5. `openelex bake.election_file --state wi --raw`
6. The resulting CSV files should be in the openelex/us/bakery folder of that repo.
