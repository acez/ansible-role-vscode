vscode
=========

A role to install and set up vscode. Currently, only macOS and maintaining vscode extensions is supported.  

Role Variables
--------------

| Variable          | Description                   |
|-------------------|-------------------------------|
| vscode_extensions | List of extensions for vscode |

Example for configuration
-------

```yaml
vscode_extensions:
  - redhat.vscode-yaml
```

License
-------

MIT
