# recipy-dev-machine
Development machine for recipy app

Prerequisites
- you need to have docker installed on your machine
- install docker-compose

Setup the docker machine:
- `docker-machine create recipy`
- `docker-machine env recipy`
- `eval $(docker-machine env recipy)`

Follow these steps to get the project running:
 - clone this repo https://github.com/AlaaAttya/recipy-api to the following path "~/recipy-workspace/recipy-api"
 - Then clone the current repo to "~/recipy-workspace/recipy-dev-machine"
 - Then run the following command `docker-compose up`
 - just wait ;)

Check if it's running
- run `docker-machine ip recipy` to get the docker machine local ip
- Then open your browser and hit the `{ip}:8090/ping`