---
title: DeleteCellInfo
series: vtctldclient
commit: a7f80a82e5d99cf00c253c3902367bec5fa40e5d
---
## vtctldclient DeleteCellInfo

Deletes the CellInfo for the provided cell.

### Synopsis

Deletes the CellInfo for the provided cell. The cell cannot be referenced by any Shard record.

```
vtctldclient DeleteCellInfo [--force] <cell>
```

### Options

```
  -f, --force   Proceeds even if the cell's topology server cannot be reached. The assumption is that you shut down the entire cell, and just need to update the global topo data.
  -h, --help    help for DeleteCellInfo
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

