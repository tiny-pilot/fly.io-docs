# _flyctl apps resume_

Resume an application

### About

The APPS RESUME command will restart a previously suspended application. 
The application will resume with its original region pool and a min count of one
meaning there will be one running instance once restarted. Use SCALE SET MIN= to raise
the number of configured instances.

### Usage
~~~
flyctl apps resume [APPNAME] [flags]
~~~

### Options

~~~
  -a, --app string      App name to operate on
  -c, --config string   Path to an app config file or directory containing one (default "./fly.toml")
  -h, --help            help for resume
~~~

### Global Options

~~~
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
      --verbose               verbose output
~~~

### See Also

* [flyctl apps](/docs/flyctl/apps/)	 - Manage apps

