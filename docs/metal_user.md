## metal user

User operations. For more information on user and account management, visit https://metal.equinix.com/developers/docs/accounts/users/ in the Equinix Metal documentation.

### Synopsis

User operations: get and add.

### Options

```
  -h, --help   help for user
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
* [metal user add](metal_user_add.md)	 - Adds a user to an organization or project
* [metal user get](metal_user_get.md)	 - Retrieves information about the current user or a specified user.

