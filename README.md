# Crazy Pizza CLI
4th homework assignment for [Pirple's NodeJS master class](https://pirple.thinkific.com/courses/the-nodejs-master-class).
This project adds CLI to a frontend website that inteacts with JSON RESTful API free of 3rd-party dependencies for a pizza-delivery company utilizing Stripe and MailGun external services.

![Logo](https://github.com/marta-krzyk-dev/CrazyPizzaAPI/blob/master/logo_small.jpg?raw=true)

## Features
- [x] View all the current menu items
- [x] View all the recent orders in the system (orders placed in the last 24 hours)
- [x] Lookup the details of a specific order by order ID
- [x] View all the users who have signed up in the last 24 hours
- [x] Lookup the details of a specific user by email address

## Screencast

[See the app in action and watch the code being explained line by line](https://www.youtube.com/watch?v=4P79amJ9D1o)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=4P79amJ9D1o
" target="_blank"><img src="http://img.youtube.com/vi/4P79amJ9D1o/0.jpg" 
alt="Pirple Node JS Master Class Homework Assignment #4" width="300" height="200" border="10" /></a>

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

`set DEBUG=* & node index.js` // Print out all debug messages

`set DEBUG=cli & node index.js` // Print out debug messages coming from cli module

3. The app informs which ports are active and that the Console is active.
4. In the console, enter a command. Find the available commands in a table below.
5. Enter `exit` to stop the app.

#### Use CLI in Chrome web browser

1. Start the application as described in **Set up**
2. Open up Chrome and and go to the address that the app printed out: `localhost:3000` or `localhost:5000`. Follow this [Basic usage scenario](https://github.com/marta-krzyk-dev/CrazyPizzaGUI/wiki#basic-usage-scenario) to learn how to navigate on the website.
2. With the website opened, click F12 to show up console.
3. Enter a command. Find the available commands in the table below.

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

### Printscreens

![man](https://github.com/marta-krzyk-dev/CrazyPizzaCLI/blob/master/PrintScreens/man_help.png?raw=true)

![menu](https://github.com/marta-krzyk-dev/CrazyPizzaCLI/blob/master/PrintScreens/menu.png?raw=true)

![list_users](https://github.com/marta-krzyk-dev/CrazyPizzaCLI/blob/master/PrintScreens/list_users.png?raw=true)

![more_user_info](https://github.com/marta-krzyk-dev/CrazyPizzaCLI/blob/master/PrintScreens/more_user_info.png?raw=true)

![list_orders](https://github.com/marta-krzyk-dev/CrazyPizzaCLI/blob/master/PrintScreens/list_orders.png?raw=true)

![more_order_info](https://github.com/marta-krzyk-dev/CrazyPizzaCLI/blob/master/PrintScreens/more_order_info.png?raw=true)
