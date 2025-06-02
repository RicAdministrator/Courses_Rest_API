# COURSES_REST_API

COURSES_REST_API is a small project that demonstrates RESTFUL API.
It only uses a js array as a datasource.
It performs CRUD operations.

## Installation

The following will be installed:
express - restful api framework
nodemon - allows automatic update of the service remowing the need to restart the service when there are updates. This will be installed globally
joi - used to validate req.body during insert/post and update/put

Open new terminal, make sure you are in root dir.
Install dependencies using command below

```console
npm i express
npm i -g nodemon
npm i joi
```

## Run in terminal to set the port

Windows

```console
set PORT=5000
```

Mac

```console
export PORT=5000
```

## To test the service, you can use one of the following commands

Open new terminal, make sure you are in root dir.

Recommended: If code is updated, no need to re-run the command

```console
nodemon index.js
```

If code is updated, you need to close the service and re-run the command.

```console
node index.js
```

