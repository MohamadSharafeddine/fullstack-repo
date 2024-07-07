Steps:
1- Create frontend-repo, backend-repo, and fullstack-repo and clone them locally
2- Create client.py in frontend-repo
3- Create server.py in backend-repo
4- Create config.yaml in fullstack-repo
5- Add submodules (frontend-repo and backend-repo) to fullstack-repo
6- Edit code in client.py, and server.py to import data from config.yaml
7- Push changes in frontend-repo and backend-repo
8- CD in fullstack-repo to submodule repo (depending on where you did changes)
9- git fetch origin
10- git pull origin main
11- CD back to fullstack-repo
12- git submodule update --remote
13- git add., commit, and push