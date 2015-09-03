git init

npm install -g grunt-cli

sudo chown -R $USER /usr/local

npm install



*** Git ***

git config user.name "melindae"

git config user.email "melindae@gmail.com"

add and commit

git remote add origin https://github.com/melindae/yourProjectName.git
git push -u origin master


*** Heroku ***

wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh

git remote add heroku git@heroku.com:your-app.git
 -or-
heroku git:remote -a shrouded-oasis-4528



git push heroku master

* git push -f heroku master // if necessary