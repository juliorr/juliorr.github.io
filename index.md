# ACME commands

## Mongo Commands

```sh
db.forms.aggregate([{$match: {"standardHeaderData.tenantId":new NumberLong("107")}}, {$out:"ENG-14330-forms"}])
sudo mongoexport --host="172.31.8.45:27017" --collection=ENG-14330-forms --db=acme_nosql_prod --out=ENG-14330-forms.json
```
