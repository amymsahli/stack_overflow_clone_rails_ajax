Smaug-Lavaflow, a Stack Overflow clone
======================================

by Amy Johnson & Gabe Finch & Mike Goren

This is a simple Ruby/Rails Stack Overflow clone.
Updated with AJAX!

Installation
------------

Install smaug-lavaflow by first cloning the repository.  
```
$ git clone http://github.com/mgoren/smaug-lavaflow.git
```

Start the database:
```
$ postgres
```

Create the databases, tables, and test environment by running the following:
```
$ rake db:create
$ rake db:migrate
$ rake db:test:prepare
```

Start the rails server:
```
$ rails s
```

In your web browser, go to http://localhost:3000

License
-------

GNU GPL v2. Copyright 2015
