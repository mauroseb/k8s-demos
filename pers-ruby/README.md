# Sample Persistent Ruby App Template

## USAGE

~~~
$ oc new-project pers-ruby-app
$ curl https://raw.githubusercontent.com/mauroseb/k8s-demos/master/pers-ruby/pers-ruby-app.yaml | oc new-app -p STORAGE_CLASS=<storage-class> -p VOLUME_CAPACITY=5Gi -f -
~~~
