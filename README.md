# DP_Nao_relacional

use FoodManager_DB
switched to db FoodManager_DB
db.createCollection("HelloWorld")
db.HelloWorld.insertOne({"_id":333222,"cliente":"Thiago Barros", "dt_nasc":"17-12-1991"})

#buscar no banco 
db.HelloWorld.find ({},{"_id":0,"COD_VENDA":1,"NOME_CLIENTE":1})
