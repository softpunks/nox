## nox document delete_by_query

Delete the documents that are the result of a query

### Synopsis

The simplest usage of delete_by_query just performs a deletion on every document that match a query

```
nox document delete_by_query [index] [flags]
```

### Options

```
  -b, --body string   json body to send with this request
  -y, --confirm       Confirm that you want to delete a document
  -h, --help          help for delete_by_query
```

### Options inherited from parent commands

```
      --config string     config file (default is $HOME/nox.yaml)
  -d, --debug             toggle debug setting
  -H, --host string       host of your elasticsearch cluster (default "localhost")
  -W, --password string   password for authentication with the cluster
  -p, --port string       port for communication with your elasticsearch cluster (default "9200")
      --pretty            toggle pretty printing of returned json (default true)
      --silent            toggle silent output
  -t, --tls               use TLS for cluster connections
  -u, --username string   username for authentication with the cluster
```

### SEE ALSO

* [nox document](nox_document.md)	 - tool for managing documents

###### Auto generated by spf13/cobra on 20-Aug-2019
