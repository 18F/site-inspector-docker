# Site Inspector, Dockerized

Site technology and capability scanning, made easy. This repository is the [Site Inspector](https://github.com/benbalter/site-inspector/) Ruby gem wrapped up in a Docker container, so you don't have to fuss with installing things like [Ruby](https://www.ruby-lang.org/) or [Nokogiri](http://www.nokogiri.org/).

## Usage

Requires [Docker](https://www.docker.com/).

```bash
docker run 18fgsa/site-inspector
```

This will print out the usage instructions. [Arguments for the `site-inspector` CLI](https://github.com/benbalter/site-inspector#command-line-usage) can then be appended to the command, like so:

```bash
docker run 18fgsa/site-inspector inspect <domain>
```
