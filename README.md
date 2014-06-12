TMCSS Score
===========

Setup
-----

```shell
gem install bundler
bundle install
```

Running the Application
-----------------------

You run the application by starting the Middleman server:

```shell
middleman s
```

If you're using Rbenv with binstubs:

```shell
./bin/middleman s
```

Building the Static Files
-------------------------

To build the static files:

```shell
middleman build
```

Or, if you're using Rbenv:

```shell
./bin/middleman build
```

Deploying
---------

If you'd like to deploy the site, add a `Rakefile` and take a look at the [Baseman](https://github.com/drewbarontini/baseman#deploying) deploy documentation.

**Note**: Be sure to remove the `Rakefile` from the `.gitignore`!
