# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
Great! You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.

2:41
Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.

2:41
If docker is working correctly, the backend should be running and able to connect to your local database.

2:41
Let's test this by pointing your browser to http://localhost:3000/api/ping

2:41
Easy Peasy! The backend is up and running.

2:42
Now, it’s time to check the frontend and make sure it’s connected to the backend.

2:42
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

2:42
Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.

2:42
Ooohh, I didn’t expect you to do this so quickly! Even your username, montegry, brings back memories. Strangely enough, they’re your memories, which I don’t know why I have.

2:42
Never mind that, though—you’re done with this dib.

2:42
Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.

2:42
It looks like your environment is ready! 😀