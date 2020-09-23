# sqlite3-easy-create
Jupyter notebook with tips for sqlite3 in python. In one place. Cuz i always forget where I saved it.

Files:
* `example_db.yml` - schema of db
* `sql_db_demo.ipynb` - notebook with recipe

Idea: Schema file can be automatically imported and used to create new sqlite3 db from scratch.

`build_create_query` and `build_insert_query` are wrapper functions for building and inserting data to db - no more long manually written queries.
Wrappers use schema to resolve number of parameters, parentheses and indexed keys in query
