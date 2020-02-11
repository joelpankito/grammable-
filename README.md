# Grammable

An Instagram clone that was built using industry-standard, test-driven development following numerous red/green/refactor cycles.

![grammable](/app/assets/images/grammable.png)


### Prerequisites

Setting up ruby on rails enviroment

[Getting Started with Rails](https://guides.rubyonrails.org/v5.0/getting_started.html)

### Installing

Once the ruby on rails enviroment has been set up.

Git clone the repository to your local machine:

HTTPS:
```
$ https://github.com/joelpankito/grammable-.git
```
SSH:
```
$ git@github.com:joelpankito/grammable-.git

```
Next, cd into the repository you cloned and install the necessary dependencies 
* In other to create your local database run:
```
rake db:create
```
```
rake db:migrate
```
* Install the necessary libraries:
```
$ bundle install
```
You will then be able to start the app locally by runnning:
```
$ rails server -b 0.0.0.0 -p 3000
```


## Built With

* [Rails](https://rubyonrails.org/) - web application framework

* [Postgres](https://www.postgresql.org/) - The database engine.

* [Bootstrap](https://getbootstrap.com/) - Bootstrap is a free and open-source CSS framework

* [JQuery](https://jquery.com/) - jQuery is a JavaScript library 

* [Devise](https://github.com/heartcombo/devise) - flexible User authentication 

* [Simple_form](https://github.com/heartcombo/simple_form) - building forms

* [FactoryGirl](https://github.com/thoughtbot/factory_bot) - test robot

* [Rspec](https://github.com/rspec/rspec-rails) - test enviroment

* [AWS Integration](https://aws.amazon.com/) - cloud storage


## Authors

* **Joel Pankito** - *Complete work* - [grammable](https://github.com/joelpankito)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



