git subtree add --prefix superset https://github.com/Devekko-Dev/superset.git master --squash

git subtree pull --prefix superset https://github.com/Devekko-Dev/superset.git master --squash



cd superset 
docker compose up --build