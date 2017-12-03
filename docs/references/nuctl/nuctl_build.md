## nuctl build

Build a function

### Synopsis


Build a function

```
nuctl build function-name [options] [flags]
```

### Options

```
      --base-image string       Name of base image. If empty, per-runtime default is used
      --build-command String    Commands to run on build of processor image
  -f, --file string             Function configuration file
      --handler string          Name of handler
  -h, --help                    help for build
  -i, --image string            Docker image name, will use function name if not specified
      --no-pull                 Don't pull base images - use local versions
      --nuclio-src-dir string   Local directory with nuclio sources (avoid cloning)
      --nuclio-src-url string   nuclio sources url for git clone (default "https://github.com/nuclio/nuclio.git")
  -o, --output string           Build output type - docker|binary (default "docker")
  -p, --path string             Function source code path
  -r, --registry string         URL of container registry (env: NUCTL_REGISTRY)
      --runtime string          Runtime (e.g. golang, golang:1.8, python:2.7)
      --version string          Docker image version (default "latest")
```

### Options inherited from parent commands

```
  -k, --kubeconfig string   Path to Kubernetes config (admin.conf)
  -n, --namespace string    Kubernetes namespace (default "default")
      --platform string     One of kube/local/auto (default "auto")
  -v, --verbose             verbose output
```

### SEE ALSO
* [nuctl](nuctl.md)	 - nuclio command line interface

###### Auto generated by spf13/cobra on 1-Nov-2017