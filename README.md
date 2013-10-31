[![Build Status](https://travis-ci.org/keisatou/amon2_bbs_tutorial.png?branch=master)](https://travis-ci.org/keisatou/amon2_bbs_tutorial)

```
carton install
sqlite3 db/development.db < sql/sqlite.sql
carton exec perl -Ilib script/bbs-server
```
access http://127.0.0.1:5000/
