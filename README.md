# plugins

The `jrnxf` marketplace for Claude Code. Each plugin lives in its own repository, and this
repository only lists them.

```bash
claude plugin marketplace add jrnxf/plugins
claude plugin install kb@jrnxf
```

To add a plugin, add an entry to `.claude-plugin/marketplace.json` with a `github` source, then
run `claude plugin validate .`.
