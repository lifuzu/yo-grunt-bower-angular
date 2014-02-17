
###Preparation:
```
$ sudo npm install -g yo grunt-cli bower
$ sudo gem install sass
$ sudo npm install -g generator-angular  # install generator
```

###Create project:
```
$ mkdir HelloWorld
$ cd HelloWorld
$ yo angular                        # scaffold out a AngularJS project
$ bower install angular-ui          # install a dependency for your project from Bower
$ grunt test                        # test your app
$ grunt serve                       # preview your app (formerly `grunt server`)
$ grunt                             # build the application for deployment
```