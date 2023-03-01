# Sagodev - HR Management

Let's discover **Sagodev HRM System**.


## This is HRM - Backend

--------------------------------

### Demo Link
https://sagodev.com/

## Getting Started

In the project you have purchase, you get backend project using **Node Js** and frontend project using **React Js**.
This project is using **Mongod DB** as database service. Before start running the project first you must make sure already installed:
- Node - https://nodejs.org/en/
- Mongo DB - https://docs.mongodb.com/manual/installation/

## Environment

Change value inside ```.env``` to your configuration.

## Install Dependencies

```shell
npm install
```

or

```shell
yarn
```

## Run project backend

```shell
npm run start
```

or

```shell
yarn start
```
EC2 script on creation to install the CodeDeploy Agent:

#!/bin/bash
```shell
sudo yum -y update
sudo yum -y install ruby
sudo yum -y install wget
cd /home/ec2-user
wget https://aws-codedeploy-us-east-1.s3.amazonaws.com/latest/install
sudo chmod +x ./install
sudo ./install auto
```

### Backend running on http://localhost:8080.

Check if CodeDeploy agent is running:

```shell
sudo service codedeploy-agent status
```

Uninstall CodeDeploy Agent:

```shell
sudo yum erase codedeploy-agent
```