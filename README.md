# Hello greetings

By now you've used many different gems with Rails and this exercise will have you connect previous knowledge with new knowledge as you get a chance to use the react-rails gem. This gem allows you to build React components as a part of your Rails JavaScript and serve it in a component, react_component, to be used in a regular ERB file.


## Built With

- Ruby
- Ruby on Rails
- Postgresql




## Getting Started

**To get a local copy up and running follow these simple example steps:**

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/)
- [Rails](https://gorails.com/)

### Setup

## Creating the hello-rails-react
- Make sure you have Ruby on Rails set up properly on your computer
- use PostgreSQL database

`$   rails new rails-react-tutorial --webpack=react -d=postgresql

$   cd rails-react-tutorial # Move into the application directory`

- Now run these command to install everything

`$   bundle install
$   rails webpacker:install
$   rails new rails-react-tutorial --webpack=react -d=postgresql
$   rails webpacker:install:react
$   rails generate react:install
$   yarn install`

## Clone the repository

`$ https://github.com/sja-thedude/hello-rails-react.git
$ cd hello-rails-react`

## Create Database

`$   rails db:create   # or
$   rake db:create
$   rails db:migrate`

## Install linters

`$  bundle init
$  bundle install`

## Run linter

`$  rubocop .
$  npx stylelint "**/*.{css,scss}"`

## Start up the web server

`$   rails s # or
$   rails server -p3000 # to visit http://localhost/`

## GEnerate Controller

`  $  rails generate controller static index
  $  rails generate controller api/messages index `

  ## Generate New React component

  `  $  rails generate react:component Greeting greeting:string
  $  rails generate react:component App`

``` sh
  git git@github.com:gabrielcoder247/hello-rails-react.git
```


## Author

👤 **GABRIEL NWACHUKWU**

- GitHub: [@codePriest](https://github.com/gabrielcoder247)
- LinkedIn: [@codepriest](https://www.linkedin.com/in/gabriel-nwachukwu-209613173/)

  Credit of the design goes to [Creative Commons license.](https://www.behance.net/gregoirevella) The Original design idea by [Gregoire Vella on Behance.](https://www.behance.net/gregoirevella)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

- Feel free to check the [issues page](https://github.com/faizi2500/recipe-app/issues).

## Show your support

- Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse for giving us this chance
