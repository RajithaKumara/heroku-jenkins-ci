# heroku-jenkins-ci

git clone https://github.com/RajithaKumara/heroku-jenkins-ci.git

cd heroku-jenkins-ci

wget http://mirrors.jenkins.io/war-stable/latest/jenkins.war

git add jenkins.war -f

git commit -m "Add jenkins.war"

git push <heroku_git_repository_url> <git_repository_branch>
