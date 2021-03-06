  ![sheltr logo](/public/LOGO.png)
# Sheltr

Sheltr provides information about services to the people who need them most, the homeless. A technical solution that reaches out to those who may have limited access to technology.

Sheltr uses PubNub's publish and subscribe SDK to allow service providers such as shelters to update crucial information in real time. As subscribers, digital billboards placed at bus stations would display information as it becomes available. This information is filtered through the Google maps API to display location and transit directions based on current traffic conditions.

  ![sheltr demo](/public/demo.gif)
# Functions

- Administrator access to available resources - ([sheltr/app/views/shelter/new.html.erb](https://github.com/christopherchan35/sheltr/blob/development/app/views/shelter/new.html.erb))
- Live update of service address, map location, resource status - ([sheltr/app/views/shelter/index.html.erb](https://github.com/christopherchan35/sheltr/blob/development/app/views/shelter/index.html.erb))
- Map with directions from origin pint to multiple locations - ([sheltr/app/views/shelter/index.html.erb](https://github.com/christopherchan35/sheltr/blob/development/app/views/shelter/index.html.erb))

# Local Usage

0. [Download Ruby](https://www.ruby-lang.org/en/downloads/) to your machine (2.3.1 or above)
1. Clone the repo to local by using `git clone https://github.com/christopherchan35/sheltr.git` in the terminal
2. Run `gem install bundler` to install the Bundler gem manager
3. Run `bundle install` to install dependencies
4. Run `rails db:create db:migrate db:seed` to set up the database
5. Run `rails s` to initiate server
6. Open [local host](http://localhost:3000) in your browser
