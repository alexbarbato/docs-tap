# tanzu build-service build logs

This command tails logs for an image resource build.

## Synopsis

Tails logs from the containers of a specific build of an image resource in the provided namespace.

The build defaults to the latest build number.
The namespace defaults to the kubernetes current-context namespace.

```console
tanzu build-service build logs <image-name> [flags]
```

## Examples

```console
tanzu build-service build logs my-image
tanzu build-service build logs my-image -b 2 -n my-namespace
```

## Options

```console
  -b, --build string       build number
  -h, --help               help for logs
  -n, --namespace string   kubernetes namespace
```

## SEE ALSO

* [tanzu build-service build](tanzu_build-service_build.md)	 - Build Commands