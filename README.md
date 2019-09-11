# User-Interaction Microservices

The sole purpose of this repository is to authenticate a user and produce a JWT token that other services can use

**Note:** 
  * You will only need docker installed on your computer to run this app

## Git Steps
1. Fork Branch
2. Open terminal and clone **forked branch**: `git clone https://github.com/<YOUR USERNAME>/user-interaction.git`
3. Go inside user-interaction directory: `cd search`
3. Add upstream repo: `git remote add upstream https://github.com/fcgl/user-interaction.git`
4. Confirm that you have an origin and upstream repos: `git remote -v`

## Build & Run App

This build should work for both macOS and Linux

1. Download docker for your operating system
2. From project root run the following command:
    * `docker-compose up --build`

## Health Endpoint

Confirm everything was ran correctly by going to the following endpoint: 
  * http://localhost:8080/health/v1/marco

