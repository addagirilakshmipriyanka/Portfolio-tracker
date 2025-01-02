# Portfolio-tracker
A Simple Portfolio Tracker application that allows users to:
1. Add, view, edit, and delete stock holdings.
2. Track the total portfolio value based on real-time stock prices.
3. View a dashboard displaying key portfolio metrics (e.g., total value,
top-performing stock, portfolio distribution).

## Description

The Simple Portfolio Tracker app helps users manage their stock investments by allowing them to add, view, edit, and delete stock holdings. It tracks the total 
portfolio value in real-time, updating with live stock prices. The app features a dashboard that provides key metrics like total value, top-performing stocks, and 
portfolio distribution. Users can easily analyze their investment performance and make informed decisions. The intuitive interface ensures seamless tracking of 
all portfolio activities.
Deployment
Deployed using Heroku

## Version
latest version: 1.5.6

## addagirilakshmipriyanka
Portfolio-tracker is built on the following main stack:

Twilio SendGrid Twilio SendGrid – Transactional Email
Ruby Ruby – Languages
Rails Rails – Frameworks (Full Stack)
PostgreSQL PostgreSQL – Databases
Puma Puma – Web Servers
JavaScript JavaScript – Languages
Devise Devise – User Management and Authentication
OmniAuth OmniAuth – User Management and Authentication
Shell Shell – Shells
Stylelint Stylelint – Code Review
Bootsnap Bootsnap – Ruby Utilities
GitHub Actions GitHub Actions – Continuous Integration

## Usage
Run the following commands:
https://github.com/addagirilakshmipriyanka/Portfolio-tracker/tree/master
cd Portfolio-tracker
bundle install
rails s
Open a browser and go to: https://localhost:3000 to view the app.

## Database setup
To start with clean database use:

cd Portfolio-tracker
rails db:drop db:create db:migrate

## Testing
cd Portfolio-tracker
run rspec

