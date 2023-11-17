# rails-react

## Description

This application includes CREATE, READ, and DELETE functionality, and is built with a React front end and the Rails web application server-side framework.

## Tools

Bootstrap v5+
React v18+
ReactDOM v18+
React Router v6+
ESBuild v0.19
Node.js v16.14.0
NPM v8.3.1
Yarn v1.22.10
Ruby v3.1.2
Rails v7.0.4
PostgreSQL v12+
Sass v1+

## Rails Web Application

Running the ```rails -h``` command yields a comprehensive suite of Rails' scripts called **generators**.

A generator script creates a directory, and populates it with the necessary files for serving a modern web application.

Included in the list of generators from running ```rails -h``` will be the ```new``` command.

Here is the script used to generate this application:

```rails new rails_react_recipe -d postgresql -j esbuild -c bootstrap -T```

## PostgreSQL Database

This application uses a PostgreSQL database, and the default database configuration values.

```rails db:create```

## Development mode

Start the application in the browser on http://localhost:3000 by running ```bin/dev```.

Rails provides an alternative bin/dev script ```bin/rails serve``` which uses the commands in ```Procfile.dev```.

## React frontend

The following command installs the necessary packages with Yarn: ```yarn add react react-dom react-router-dom```.

**Note:** React builds the user interface, ReactDOM enables interaction between React and the browser DOM, React Router handles the navigation.

## Acknowledgements

This application was created by following [this](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-ruby-on-rails-v7-project-with-a-react-frontend-on-ubuntu-20-04) tutorial.
