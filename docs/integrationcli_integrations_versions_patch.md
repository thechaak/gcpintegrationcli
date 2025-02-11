## integrationcli integrations versions patch

Patch an integration flow version

### Synopsis

Patch an integration flow version

```
integrationcli integrations versions patch [flags]
```

### Options

```
  -f, --file string   Integration flow JSON file content
  -h, --help          help for patch
  -n, --name string   Integration flow name
  -v, --ver string    Integration flow version
```

### Options inherited from parent commands

```
  -a, --account string       Path Service Account private key in JSON
      --apigee-integration   Use Apigee Integration; default is false (Application Integration)
      --disable-check        Disable check for newer versions
      --no-output            Disable printing API responses from the control plane
  -p, --proj string          Integration GCP Project name
  -r, --reg string           Integration region name
  -t, --token string         Google OAuth Token
      --verbose              Enable verbose output from integrationcli
```

### SEE ALSO

* [integrationcli integrations versions](integrationcli_integrations_versions.md)	 - Manage integrations flow versions

###### Auto generated by spf13/cobra on 18-Jan-2023
