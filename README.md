# Homeflow

## Setup

Create a file called `credentials.json` in the project root (`homeflow/credentials.json`).
The contents should look like this:

```
{
  "smartThingsUrl": "SMART_THINGS_URL_ENDPOINT",
  "smartThingsSecret": "APP_SECRET"
}
```

## Build instructions

```
$ yarn install
$ yarn run start:dev
```

Then open `localhost:3001` in your browser to view.
