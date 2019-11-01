# Chitter-Chatter
A messaging app that plays sounds and animations with every message.    

## Features
Users are able to send and recieve messages with other users. When a user types a letter on the site, a sound and animation will play. Users can replay the sounds and animations that play when other users send them messages. Users are also able to edit their information.  

## Demo
Demo Video coming soon!

## Built with
 *Back-end*
- [Ruby on Rails](https://rubyonrails.org) - Server Framework
- [PostgreSQL](https://www.postgresql.org) - Database

*Front-end*
- Vanilla HTML, Custom CSS for styling
- [webpack](https://webpack.js.org) - Script and Asset bundler
- [Paper.js](http://paperjs.org/) - Vector Graphics Scripting Library
- [howler.js](https://howlerjs.com) - JavaScript Audio Library


## Installation
*Requirements*
 - [Node.js](https://nodejs.org/en/)
 - [Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/)
 - [PostgreSQL](https://www.postgresql.org)


In your clone/fork of this repo: 
```bash
bundle install
rails db:create #creates database
rails db:migrate #creates tables in db
rails db:seed #creates seed data
rails s #to run the server
```

The instructions for the front-end of this app are [here](https://github.com/Giagnus64/Chitter-Chatter-Front-End). You'll need to clone/fork both repos and change your fetch URLS to local if you want to change the API. Otherwise, the app will make calls to the API hosted on heroku. 


## License
[MIT](https://choosealicense.com/licenses/mit/)