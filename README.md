# assignment_10
1) What command will show all the docker containers running?
docker ps
2) What command is used to locally register a file change with git?
git add <filename>
3) What command is used to get the default Vagrantfile?
vagrant init <boxname>
4) What command would be used to create and set your working tree to a branch called question_four?
git checkout -b question_four
5) What command would you use to interact with a container named question_five via bash?
docker exec -it question_five /bin/bash
6) How would you start a compose session that was NOT logging to stdout?
docker-compose up -d
7) Write a single line bash function that would wait for any single character of user input.
wait_for_char() { read -n 1 -s -r -p "Press any key to continue..."; }
8) What is an alternative to docker compose?
Kubernetes
9) What is the github mascot?
Octopus named "Octocat"
10) What is one of the principles of DevOps?
Collaboration between Development and Operations teams.

