# pnpx

> Directly execute binaries from npm packages, using `pnpm` instead of `npm`.
> Note: This command is deprecated! Use `pnpm exec` and `pnpm dlx` instead.
> More information: <https://cuyl.github.io/pnpm.github.io/pnpx-cli>.

- Execute the binary from a given `npm` module:

`pnpx {{module_name}}`

- Execute a specific binary from a given `npm` module, in case the module has multiple binaries:

`pnpx --package {{package_name}} {{module_name}}`

- Display help:

`pnpx --help`
