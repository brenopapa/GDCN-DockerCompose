This docker compose file creates two docker containers, using postgres and gooddata.cn latest docker images.

The postgres database is setup with a script that creates and populates sample tables for GoodData CN usage.

After both containers are running, just hit localhost:3000 and start using GoodData CN with your sample database.

The docker compose file might need some IP adjustments.

All images can be found in docker hub.