# docker-heroku-cli

Just type `./heroku` inside the project directory and it tries to build a docker container image that includes a runnable Heroku CLI and run it after that.

> Maybe you have to make it executable first by running something like `chmod u+x heroku` 

For example you can use different logins to heroku using this little tool.
Your login will be saved in .netrc inside your project directory.

If you need more than one login you could clone this multiple times and have one login per project directory.

# No unicorn
This is an experimental tool so it may be far from perfect. 
But it solved my problem to use different login for heroku without logging my self out from heroku using my locally installed Heroku Toolbelt when using their CLI.

# Requirement
A recent version of docker installed on your machine. I've used Docker 17.03.1-ce on MacOS Sierra 10.12.4 to build this.

# Tell me
I would be happy to hear if it helped you or you think that something should be changed.
