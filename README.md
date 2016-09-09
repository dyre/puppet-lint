# puppet-lint

Make sure you mount a volume with the code you would like to lint into /modules.

### List options
docker run --rm dyre/puppet-lint --help

### Show version:
docker run --rm dyre/puppet-lint -v

### Lint:
docker run --rm -v /path/to/your/modules/:/modules/ dyre/puppet-lint
