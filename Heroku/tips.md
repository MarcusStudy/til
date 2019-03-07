#Tips
## Go to application on heroku
```
$ heroku open
```

## Access to the Postgresql on heroku
```
$ heroku pg:psql
```

## Run query without logging in to Postgresql
```
$ heroku pg:psql -c "select count(*) from table_name"
```

## Check heroku log
```
$ heroku logs
```

## Change the timezone on heroku
```
$ heroku config:add TZ="America/Vancouver"
```

## Check the timezone on heroku
```
$ heroku run bash
heroku-app$ date
```

## See all configs
```
$ heroku config
```

## See config
```
$ heroku config:get ENV_NAME
```

## Set config
```
$ heroku config:set ENV_NAME=value
```

## Set some configs same time
```
$ heroku config:set ENV_NAME_1=value1 ENV_NAME_2=value2
```

## Delete config
```
$ heroku config:unset ENV_NAME
```

## Delete some configs same time
```
$ heroku config:unset ENV_NAME_1 ENV_NAME_2
```

## Check hours on Heroku
```
$ heroku ps -a appname
```
