---
title: ReloadSchemaKeyspace
series: vtctldclient
commit: 9a3d0f4a69a840cfa2cb86654abd4afa0be6e0aa
---
## vtctldclient ReloadSchemaKeyspace

Reloads the schema on all tablets in a keyspace. This is done on a best-effort basis.

```
vtctldclient ReloadSchemaKeyspace [--concurrency=<concurrency>] [--include-primary] <keyspace>
```

### Options

```
      --concurrency uint32   Number of tablets to reload in parallel. Set to zero for unbounded concurrency. (default 10)
  -h, --help                 help for ReloadSchemaKeyspace
      --include-primary      Also reload the primary tablets.
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

