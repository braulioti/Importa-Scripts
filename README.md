# [ImportScripts v1.0.0](https://github.com/braulioti/Import-Scripts)
### Simple project for import database scripts

[![Twitter: @braulio_info](https://img.shields.io/badge/contact-@braulio_info-blue.svg?style=flat)](https://twitter.com/braulio_info)
[![Build Status](https://travis-ci.org/braulioti/Import-Scripts.svg?branch=master)](https://travis-ci.org/braulioti/Import-Scripts)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8d587cef062549b9af40f1d3c1c74c0d)](https://www.codacy.com/app/braulioti/Import-Scripts?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=braulioti/Import-Scripts&amp;utm_campaign=Badge_Grade)

- Import scritps is a simple project for execute SQL Scripts. This project basicly import a script
file, crop by ";" and execute in database. Import Scripts is  
created and maintained by [Bráulio Figueiredo](http://braulioti.com.br).
Stay up to date with the latest release and announcements on Twitter:
[@braulio_info](http://twitter.com/braulio_info).

## Changelog

- [1.0.0 Versioning PostgreSQL database files using script list](https://github.com/braulioti/Import-Scripts)

## Versioning

Import Scripts will be maintained under the Semantic Versioning guidelines as much as possible.
Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions, including new icons, without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org.

## Author
- Email: braulio@braulioti.com.br
- Twitter: http://twitter.com/braulio_info
- GitHub: https://github.com/braulioti
- Website: http://braulioti.com.br

## Using this project

### For import script file
`java -jar import-scripts-0.2.0.jar host:port/database username password script_file`

### For versioning folder

- create `files.conf` file with all scripts files in execution order

`java -jar import-scripts-0.2.0.jar folder host:port/database username password folder`
