## config-server from Git:

run app on dev environment with `-Dspring.profiles.active=dev` VM argument
   
config server from repo can be reached on http://localhost:8888/config-dev/dev

## config-server from local:

For local repo a file with name `config-test.yml` needs to be set up in `${user.home}/Desktop/config` with any desired content.
This config file needs to be initialized with git init and also committed with git commit in order to be able to use it

run app on test environment with `-Dspring.profiles.active=native` VM argument
   
config server from repo can be reached on http://localhost:8888/config-test/test
