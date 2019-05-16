# Crazy Pizza CLI
4th homework assignment for [Pirple's NodeJS master class](https://pirple.thinkific.com/courses/the-nodejs-master-class).
This project adds CLI to a frontend website that inteacts with JSON RESTful API free of 3rd-party dependencies for a pizza-delivery company utilizing Stripe and MailGun external services.

![Logo](https://github.com/marta-krzyk-dev/CrazyPizzaAPI/blob/master/logo_small.jpg?raw=true)

## Features
- [ ] View all the current menu items
- [ ] View all the recent orders in the system (orders placed in the last 24 hours)
- [ ] Lookup the details of a specific order by order ID
- [ ] View all the users who have signed up in the last 24 hours
- [ ] Lookup the details of a specific user by email address

## Manual

### Set up
0. Download the project.
1. Open the command prompt (for Windows, click Start icon and type in 'cmd') and go to the project directory.eg. :

`cd C:/CrazyPizzaCLI`

2. Run the app:
`node index.js`

Optionally, one can set the environment as command line argument (with value of 'production' or 'staging'). The default is 'staging'.

`node index.js production` (for Windows)

`NODE_ENV=production node index.js` (for Linux)

Optionally, one can set DEBUG variable to print out messages in the console. (for Windows):

`set DEBUG=* & node index.js` // Print out all debug messages

`set DEBUG=helpers & node index.js` // Print out debug messages coming from debug module

3. The app informs which ports are active and that the Console is active.
4. In the console, after prompt sign `>` enter a command. Find the available commands in a table below.
5. Enter `exit` to stop the app.

## Use CLI in Chrome web browser

1. Start the application as described in ##Set up##.
2. Open up Chrome and and go to the address that the app printed out: `localhost:3000` or `localhost:5000`. Follow this [Basic usage scenario](https://github.com/marta-krzyk-dev/CrazyPizzaGUI/wiki#basic-usage-scenario) to learn how to navigate on the website.
2. With the website opened, click F12 to show up console.
3. After prompt sign `>` enter a command. Find the available commands in a table below.

### CLI Commands

|Command|Description|
|-------|-----------|
|`exit`| Kill the CLI (and the rest of the application) |
|`man`| Show this help page |
|`help`| Alias of the "man" command |
|`menu`| View all the current menu items |
|`list orders`| Show all the recent orders in the system (orders placed in the last 24 hours) |
|`more order info --{orderId}`| Show details of a specified order |
|`list users`| Show a list of all the users who have signed up in the last 24 hours |
|`more user info --{userEmail}`| Show detailed info of a specified user |

