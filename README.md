# Bad Copenheimer
A Python impelentation of a discord bot that acts as a server scanner.

This is a discord bot that will scan ip adresses to see if they are minecraft servers and will post the results in your channel.

## Current Status

Moving the bot to a slash command basis. Ultimate goal of clicking a link to add the bot then downloading the file of servers.

## Installation

[Installation Page](https://www.github.com/Pilot1782/bad_copenheimer/wiki/Installation)

## Usage
The first time you use this bot, run 

>!help

This shows all of the commands you can use and their usage. Then to create your server list, run:

>!mc

This will get a list of all active minecraft servers, you may want to set the threads higher than the current value. This will take several hours to complete.

## Important

In order for !find and !status to work properly the server should have enable-query=true in the server.properties file

### All Possible Commands

>!help

>!find

>!status

>!mc


# Todo

**1:** Use send login packets to check if the server is whitelisted

**2:** Create a [Meteor Client](https://github.com/MeteorDevelopment/meteor-client) addon and implement the scanner results into the addon allowing you to join servers based on "whitelist, modded, vinilla etc."

**3:** Implement Slash Commands
