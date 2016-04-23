#### psmysqlworkbengt
#####Administration
######Impact of setting
connection->advanced->use ansi quotes to quote identifiers(so it only accept fewer formats)
######option file
performance->
```
query_cache_limit
query_cache_min_res_unit
query_cache_size
query_cache_type
```
#####Development
######Query menu limit rows
query->limit rows

######transaction
in workbench, all query in a tab share single transaction
######Toolbar resultset grid
wrap cell content //show all contents of long text  
fetch rows  //show next batch records


#####Data modeling
######Create EER
start-> models(three icons),new models, existing models,create EER from database(script)  
step5 select objects->
######Forwawrd engineering
EER model->Database->forward engineering->drop before create
######schema transfer
schema transfer wizard
######schema compare
compare schemas
