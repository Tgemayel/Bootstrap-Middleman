## Bootstrap Middleman Boilerplate

This is a middleman template to get a static site up and running quickly with Bootstrap, Haml, Sass and Bower. 

Some goodies this template provides:

* Middleman
* Bootstrap
* Haml/Sass
* Bower 
* Livereload 
* Typekit 
* Google Analytics


## Usage 

Install this project 

```
$ git clone git://github.com/Tgemayel/Bootstrap-Middleman.git ~/.middleman/boostrap
```

Create your project  

```
$ middleman init [projectname] --template=bootstrap

$ cd [projectname]

# install assets from bower
$ bower install    
```

Once you're project has been created, cd to that directory and run 


```
# Install the gems 
$ bundle install

# Run the server 
$ bundle exec middleman server
```

Viola. You will see the output from Middleman now running locally at [http://localhost:4567](http://localhost:4567)



