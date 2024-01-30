# SOCIALSYNC

A project that aims to create an "easy" way to participate in the ActivityPub "Fediverse".

## Install

Quick start: [Remix on Glitch](#setup-glitch)

Clone the repo:
`git clone git@github.com:abdullah1308/socialsync.git`

Enter folder:
`cd socialsync`

Install node dependencies:
`npm install`

Before running, set your configuration.

To start, run:
`npm start`

## Config

In the .env file, put:

```
USERNAME=yourusername
PASS=yourpasswordforadmintools
DOMAIN=yourdomainname
PORT=3000
```

## Login

To login, visit `https://yourdomain.com/private` and provide the username and password from your .env file

### Setup: Glitch

Glitch will provide you with hosting for your instance of socialsync

Click this link -> [Remix this project on Glitch](https://glitch.com/edit/#!/import/github/abdullah1308/socialsync) <--

A copy of the socialsync code was sent to a new, unique, owned-by-you web server and it started getting set up. You just need to make it yours by following these steps:

1. First, make sure the URL of your Glitch project is the one you like. You can change it in the "Settings" menu.
2. Then, configure the options [as described above](#config) using the .env editor.
3. Finally, login to the dashboard at `https://yourdomain.glitch.me/private`.
