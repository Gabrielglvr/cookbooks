# eXecute Npm Package Binaries (NPX)

## CLI

### Installation

#### NPM

```sh
npm install -g npx
```

### Commands

```sh
npx -h
```

### Tips

#### Registry

```sh
#
npm_config_registry=[] \
  npx [package]

# or
npx --userconfig ~/.npmrc-[vendor] [package]
```
