## kubectl-testkube migrate

manual migrate command

### Synopsis

migrate command will run migrations greater or equals current version

```
kubectl-testkube migrate [flags]
```

### Options

```
  -h, --help               help for migrate
      --namespace string   testkube namespace (default "testkube")
```

### Options inherited from parent commands

```
  -a, --api-uri string   api uri, default value read from config if set (default "http://localhost:8088")
  -c, --client string    client used for connecting to Testkube API one of proxy|direct (default "proxy")
      --oauth-enabled    enable oauth
      --verbose          show additional debug messages
```

### SEE ALSO

* [kubectl-testkube](kubectl-testkube.md)	 - Testkube entrypoint for kubectl plugin

