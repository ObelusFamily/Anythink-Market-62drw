# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Click the [create your own codespace](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=543767000) link you received from your manager. (No need to change anything in the default options, just click on the `Create codespace` button and wait for it to boot)
2. When your codespace is up and running, run `docker-compose up` in your codespace's terminal to load Anythink's backend and frontend.
3. Once docker-compose finishes loading up, the backend should be running and able to connect to the database. Test this by pointing your browser to https://obelusfamily-anythink-market-62drw-qvxjq9x546pfxv4r-3000.githubpreview.dev/api/ping. If everything is done properly, you should see this message on the link: `{"msg":"Pong! Seems like Everythink is working, great job!"}`.
4. To check the frontend and make sure it’s connected to the backend, go to https://obelusfamily-anythink-market-62drw-qvxjq9x546pfxv4r-3001.githubpreview.dev/register and create a new user.

That's it! Your development environment is ready :smiley:
