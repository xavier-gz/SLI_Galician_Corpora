***SLI_GalWeb.1.0.tar.gz*** file has been split into 25MB parts with the ***split*** command:

```console
$ split -b 25M -d SLI_GalWeb.1.0.tar.gz SLI_GalWeb.1.0.tar.gz.part
```

To rejoin these parts after download, you can use the ***cat*** command:

```console
$ cat SLI_GalWeb.1.0.tar.gz.part* > SLI_GalWeb.1.0.tar.gz
