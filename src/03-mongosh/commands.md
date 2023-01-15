## Connect to container

docker compose exec mongodb bash

## Connect with mongosh

mongosh ""

show dbs
show collections

use('sample_training');

db.zips.find({
state : "NY"
}).
