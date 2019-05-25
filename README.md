# convert-postman-jmeter

![GitHub issues](https://img.shields.io/github/issues/sercheo87/convert-postman-jmeter.svg)
![npm](https://img.shields.io/npm/v/3.svg)
![NPM](https://img.shields.io/npm/l/1.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/sercheo87/convert-postman-jmeter.svg)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/sercheo87/convert-postman-jmeter.svg)

This tool convert projects [Postman](https://www.getpostman.com) to [JMeter](https://jmeter.apache.org)

## Installation

```bash
npm i convert-postman-jmeter -g
```

## Usage

```bash
$ convert-postman-jmeter
Usage: convert-postman-jmeter -p [file] -j [file]

Options:
  --help          Show help                                            [boolean]
  --version       Show version number                                  [boolean]
  -p, --postman   Load project postman                                [required]
  -j, --jmeter    Output project JMeter
  -o, --override  Override project JMeter                       [default: false]

Copyright 2019
```

### Options

    -p,--postman        File name of project Postman exported.

    -f,--jmeter         File name to output generated project JMeter.

## Known Issues

For issues create o find in [issues page](https://github.com/sercheo87/convert-postman-jmeter/issues).