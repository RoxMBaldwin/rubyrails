# Server Side Crud
## Learn a new Language
You will teach yourself a new server side language/web framework and build a RESTful CRUD JSON API in said language/framework.
- [ ] * Get language and framework approved by an instructor

- [ ] * Choose your language

- [ ] **Write/Compile/Run Hello World in a new Language**

- [ ] **Implement a RESTful CRUD JSON API in a new Language**

## Steps to CRUD in a new Language / Framework
- [ ] Choose a Language (Any server side language except JavaScript)

  - [ ] Setup Development Environment
  - [ ] Write / Compile / Run Hello World

- [ ] Choose a Server Side Web Framework
  * [Web Application Frameworks](https://github.com/showcases/web-application-frameworks?s=stars)

  * [Hot Frameworks](http://hotframeworks.com/)

  * [Languages and Frameworks you should learn in 2016](https://tutorialzine.com/2015/12/the-languages-and-frameworks-you-should-learn-in-2016)

- [ ] Create a RESTful CRUD JSON API using a framework in chosen language

  - [ ] Complete a tutorial on a given language/framework that creates a RESTful CRUD JSON API

  - [ ] Data must be stored in a database of some kind
        *can be anything: MySQL, Postgres, Mongo, etc*

  - [ ] API must return JSON

  - [ ] Create a repo, push to Github, and submit to learn

[CJ's tips](https://gist.github.com/w3cj/de4982a126ea52b3df326660a240ad7e)

# Build a Server with Ruby on Rails

Install Ruby Version Manager (RVM)
*RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems.*
```
$ \curl -sSL https://get.rvm.io | bash -s stable
```
**Ruby will automatically use bash to store the configuration information.**
If you are using Zsh or anything other than Bash, copy and paste the information from the bash.rc and bash-profile into the zsh.rc

Load RVM into your shell sessions as a function
```
$ source ~/.rvm/scripts/rvm

$ rvm user gemsets
```

Test - should return rvm is a function
```
$ type rvm | head -n 1
```

Install [Ruby](https://rubygems.org/)
```
$ rvm install 2.1.1
```
or, install latest stable version of ruby
```
rvm install ruby --latest
```

Install [Rails](http://guides.rubyonrails.org/getting_started.html)
```
gem install rails -v 4.1.8
```
to test the version
```
rails -v
```

Install [Bundler](http://bundler.io/)
```
gem install bundler
```

*if you run $ bundle and get:*
```
Can't install RMagick 0.0.0. Can't find Magick-config . . .
```
 install the Image Magick dependency
 ```
 brew install imagemagick
 ```
