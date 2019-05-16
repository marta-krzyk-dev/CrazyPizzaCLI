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

Optionally, one cat set DEBUG variable to print out messages in the console.

`set DEBUG=* & node index.js` (for Windows)

3. The app informs which ports are active.
4. Open up a web browser and go to the address printed out in point 3: `localhost:3000` or `localhost:5000`. 
Follow the Basic scenario below to learn how to navigate on the website.
5. Push `Ctrl` + `C` in the console to stop the app.

### Basic scenario:

1. Start the application as described in ##Set up##.
2. In web browser in Chrome click F12 to show up console or work in the console.
3. 

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

