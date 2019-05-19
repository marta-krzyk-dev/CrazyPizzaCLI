# Crazy Pizza CLI
4th homework assignment for [Pirple's NodeJS master class](https://pirple.thinkific.com/courses/the-nodejs-master-class).
This project adds CLI to a frontend website that inteacts with JSON RESTful API free of 3rd-party dependencies for a pizza-delivery company utilizing Stripe and MailGun external services.

![Logo](https://github.com/marta-krzyk-dev/CrazyPizzaAPI/blob/master/logo_small.jpg?raw=true)

## Requirements
- [] Create a new empty repository with a /test folder, and an /app folder.
- [] Inside of the app folder, create a library (lib.js) and fill it with simple functions. These can serve any purpose you wish, such as generating a random number, or checking whether or not a string is a palindrome. Really, any kind of functions will do.
- [] Inside the /test folder, create a simple test runner, and then write tests for the functions in your lib.js file. You should try to test that they return (or callback) the correct value when passed valid parameters, and that they return a predictable value (and don't crash) when passed invalid parameters.

## Manual

### Set up
0. Download the project.
1. Open the command prompt (for Windows, click Start icon and type in `cmd`) and go to the project directory.eg. :

`cd C:/CrazyPizzaCLI`

2. Run the app:

`node index.js`

Optionally, one can set the environment as command line argument (with value of 'production' or 'staging'). The default is 'staging'.

`node index.js production` (for Windows)

`NODE_ENV=production node index.js` (for Linux)

Optionally, one can set DEBUG variable to print out messages in the console. (for Windows):

`set DEBUG=* & node index.js // Print out all debug messages`

`set DEBUG=cli & node index.js // Print out debug messages coming from cli module`

3. The app informs which ports are active and that the Console is active.
4. In the console, enter a command. Find the available commands in a table below.
5. Enter `exit` to stop the app.

## Printscreens

