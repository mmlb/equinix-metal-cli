## metal hardware-reservation

Hardware reservation operations. Information on reserving hardware on Equinix Metal is available on https://metal.equinix.com/developers/docs/deploy/reserved/.

### Synopsis

Hardware reservation operations: get, move.

### Options

```
  -h, --help   help for hardware-reservation
```

### Options inherited from parent commands

```
      --config string        Path to JSON or YAML configuration file
      --exclude strings      Comma separated Href references to collapse in results, may be dotted three levels deep
      --filter stringArray   Filter 'get' actions with name value pairs. Filter is not supported by all resources and is implemented as request query parameters.
      --include strings      Comma separated Href references to expand in results, may be dotted three levels deep
  -o, --output string        Output format (*table, json, yaml)
      --search string        Search keyword for use in 'get' actions. Search is not supported by all resources.
      --sort-by string       Sort fields for use in 'get' actions. Sort is not supported by all resources.
      --sort-dir string      Sort field direction for use in 'get' actions. Sort is not supported by all resources.
      --token string         Metal API Token (METAL_AUTH_TOKEN)
```

### SEE ALSO

* [metal](metal.md)	 - Command line interface for Equinix Metal
* [metal hardware-reservation get](metal_hardware-reservation_get.md)	 - Lists a Project's hardware reservations or the details of a specified hardware reservation.
* [metal hardware-reservation move](metal_hardware-reservation_move.md)	 - Moves a hardware reservation.

