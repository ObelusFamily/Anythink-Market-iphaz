Hello! Welcome to Anythink. 

At Anythink, our engineers work with a development environment that's hosted in the cloud called Github Codespace. No need to install anything on your own computer!

## Codespace setup
Go ahead and create your own codespace [here](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=551870316).
(No need to change anything in the default options, just click on the Create codespace button and wait for it to boot)

Once your codespace is up and running, you can run docker-compose up in your codespace's terminal to load Anythink's backend and frontend. 
## Backend 
Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
Make sure you test the back-end by pointing your browser to https://obelusfamily-anythink-market-iphaz-6vwv6gxv544c56x4-3000.githubpreview.dev/api/ping

## Frontend
Go ahead and check if the frontend is up and running. If everything is working properly, you’ll be able to create a new user on https://obelusfamily-anythink-market-iphaz-6vwv6gxv544c56x4-3001.githubpreview.dev/register

## Conclusion
Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.