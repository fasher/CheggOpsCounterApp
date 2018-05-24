# Chegg Ops - Counter app - Exercise submission 

Hello Chegg guys,
I have dockerized the application and created a docker-compose file that would make it easy to start the application. 

Prerequisite to run this is to have docker-engine and docker-compose installed. 

in order to start the env:
1. git clone the repo
2. cd into repo dir
3. docker-compose build
4. docker-compose up

the up is exposed on port 80
e.g.: 
```
ubuntu@ip-172-31-20-253:~/CheggOpsCounterApp/webserver$ curl localhost:80
~                                                                                             │Hello, This page has been viewed 2 tiems <br> Hostname: 08afb84db3fa
```
