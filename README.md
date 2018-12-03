# meta-yarn

[![Greenkeeper badge](https://badges.greenkeeper.io/mateodelnorte/meta-yarn.svg)](https://greenkeeper.io/)

yarn plugin for [meta](https://github.com/mateodelnorte/meta)


## Usage

```
➜  meta git:(master) ./bin/meta

  Usage: meta [options] [command]


  Commands:

    git         manage your meta repo and child git repositories
    yarn         run yarn commands against your meta and child repositories
    help [cmd]  display help for [cmd]

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```
```
➜  meta git:(master) ./bin/meta yarn

  Usage: meta-yarn [options] [command]


  Commands:

    install       yarn install meta and child repositories
    link [--all]  yarn link all child packages used within meta repo or other child repos
    help [cmd]    display help for [cmd]

  Options:

    -h, --help  output usage information
```
