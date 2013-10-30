```
carton install
sqlite3 db/development.db < sql/sqlite.sql
carton exec perl -Ilib script/bbs-server
```
access http://127.0.0.1:5000/
