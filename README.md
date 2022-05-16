## Express web server application

Set up your component repository to use the node/npm/express stack. With the Docker Generic scaffolder, developers can create a Dockerfile that allows setting up a NodeJS application that starts an  [Express](https://expressjs.com/) server. 

### Prerequisites

-   CodeNOW account.
-   Application previously created.
-   Basic knowledge of Dockerfile. If the Dockerfile introduced in this article fits your needs, there is no need to know about Dockerfiles.

### Steps

1. Create a component with the Docker Generic scaffolder
2. Clone the component's Git repository to your local machine
3. Clone the current repository to your local machine
4. Copy the contents of the current repository (now on your local machine) to the component's Git repository
5. **NOTE: do not copy `.git`** file

### Scaffolder defaults
The present scaffolder contains a simple Express server application with the following configuration choices:

-   Programs will run with NodeJS version 18.
-   Node will run  `./bin/www`  on startup.
-   `npm`  is used as package manager.
-   The application uses the Express web server framework (version 4.16).
-   `package.json`  holds the application dependencies and their versions.
-   Your Express/NodeJS code can directl be in the home directory of the Git repository.
-   Jade is used as a templating language for web pages.
-   The  [Express's Router module](https://expressjs.com/en/guide/routing.html)  is used for routing.
-   The application starts on port 80.


### Further customization
Customize further to reflect additional constraints or requirements:

-   Update version of the dependencies.
-   Update the dependencies.
-   Add deployment configuration files in the  `/codenow/config/`  folder. Files in this folder are deployed with the application so the application can access them at runtime. For more information, see  [Deployment configurations](https://docs.codenow.com/docs/admin-manuals/deployment-configurations#use-cases).