# Teamcity docker installation

DOCKER WITH MYSQL AND ONE AGENT
------------
1. Teamcity (`80` port by default)
2. MYSQL `teamcity-mysql` host accessible from docker `teamcity` network
3. Teamcity agent connected to server via docker `teamcity` network


SHARED FOLDERS
------------
1. Teamcity ./server/data and ./server/logs
2. Mysql ./db/data
3. Teamcity agent ./agent_1/data


DOCKER WITH MYSQL AND THREE AGENTS
------------
1. Teamcity (`80` port by default)
2. MYSQL `teamcity-mysql` host accessible from docker `teamcity` network
3. Teamcity agent #1 connected to server via docker `teamcity` network
3. Teamcity agent #2 connected to server via docker `teamcity` network
3. Teamcity agent #3 connected to server via docker `teamcity` network
