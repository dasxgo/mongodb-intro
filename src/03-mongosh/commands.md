## Conect to container

'''sh
docker-compose exec mongodb bash
'''

## Conect with mongosh

'''sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://dasxgo:das1805@cluster0.z3indip.mongodb.net/"
'''

'''sh
show dbs
show collections
'''

'''sh
use('store')
db.products.find()
'''