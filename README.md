#Tech Assessment Laravel PHP
Solution to Temper users onboarding flow analysis challenge, The solution comprise two containarized applications, a vuejs frontend client and a lumen server application providing resouces via api to the frontend client
### Running app ###

### Let me see now ###

* Clone repository: `git clone https://github.com/PrinceDavis/temper-onboarding.git`
* Switch into project directory `cd temper-onboarding`
* start app: `docker-compose up`
* Direct your browser to 'http://localhost/'

**Note**: I asummed you have docker running on your system ):
### Let me see behind the curtain###

* Clone repository: `git clone https://github.com/PrinceDavis/temper-onboarding.git`
* Switch into project directory `cd temper-onboarding`

*clone frontend : `git clone https://github.com/PrinceDavis/temper-onboarding-frontend.git`

*clone frontend : `git clone https://github.com/PrinceDavis/temper-onboarding-backend.git`

* rename docker-compose-dev.yml to docker-compose.yml
* start app: `docker-compose up`

#### Run Test####
*Windows system: `docker run --rm -it -v \
path/to/project/onboarding-backend/application:/opt -w /opt  \
ossaijad/tob vendor/bin/phpunit`

*Non Windows system: `docker run --rm -it -v \
$(pwd)/onboarding-backend/application:/opt -w /opt  \
ossaijad/tob vendor/bin/phpunit`

* Happ coding ):