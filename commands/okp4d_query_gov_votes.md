## okp4d query gov votes

Query votes on a proposal

### Synopsis

Query vote details for a single proposal by its identifier.

Example:
$ okp4d query gov votes 1
$ okp4d query gov votes 1 --page=2 --limit=100

```
okp4d query gov votes [proposal-id] [flags]
```

### Options

```
      --count-total       count total number of records in votes to query for
      --height int        Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help              help for votes
      --limit uint        pagination limit of votes to query for (default 100)
      --node string       &lt;host&gt;:&lt;port&gt; to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
      --offset uint       pagination offset of votes to query for
  -o, --output string     Output format (text|json) (default "text")
      --page uint         pagination page of votes to query for. This sets offset to a multiple of limit (default 1)
      --page-key string   pagination page-key of votes to query for
      --reverse           results are sorted in descending order
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID (default "okp4d")
```

### SEE ALSO

* [okp4d query gov](okp4d_query_gov.md)	 - Querying commands for the governance module
