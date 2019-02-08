# XL Deploy Unix Process plugin

[![Build Status][xld-unix-process-plugin-travis-image] ][xld-unix-process-plugin-travis-url]
[![Codacy Badge][xld-unix-process-plugin-codacy-image] ][xld-unix-process-plugin-codacy-url]
[![Code Climate][xld-unix-process-plugin-code-climate-image] ][xld-unix-process-plugin-code-climate-url]
[![License: MIT][xld-unix-process-plugin-license-image] ][xld-unix-process-plugin-license-url]
![Github All Releases][xld-unix-process-plugin-downloads-image]

[xld-unix-process-plugin-travis-image]: https://travis-ci.org/xebialabs-community/xld-unix-process-plugin.svg?branch=master
[xld-unix-process-plugin-travis-url]: https://travis-ci.org/xebialabs-community/xld-unix-process-plugin
[xld-unix-process-plugin-codacy-image]: https://api.codacy.com/project/badge/Grade/21ad78cccf7b47839547a1fcd9e342aa
[xld-unix-process-plugin-codacy-url]: https://www.codacy.com/app/joris-dewinne/xld-unix-process-plugin
[xld-unix-process-plugin-code-climate-image]: https://codeclimate.com/github/xebialabs-community/xld-unix-process-plugin/badges/gpa.svg
[xld-unix-process-plugin-code-climate-url]: https://codeclimate.com/github/xebialabs-community/xld-unix-process-plugin
[xld-unix-process-plugin-license-image]: https://img.shields.io/badge/License-MIT-yellow.svg
[xld-unix-process-plugin-license-url]: https://opensource.org/licenses/MIT
[xld-unix-process-plugin-downloads-image]: https://img.shields.io/github/downloads/xebialabs-community/xld-unix-process-plugin/total.svg

# Preface #

This documented describes the Unix Process Plugin which supports the deployment of a standlone process to a Unix envionment. Assumes process artifact is a folder which is deployed to a home directory with start and stop scripts.

See the **XL Deploy Reference Manual** for background information on XL Deploy and deployment concepts.

## Requirements ##

* **Requirements**
    * **XL Deploy** 5.0.0

## Installation ##

Place the plugin JAR file into your `SERVER_HOME/plugins` directory.  

## Types ##

+ unix.ProcessContainer
  * `home` (Home directory of the process)
  * `startCommand` (Start command)
  * `stopCommand` (Stop command)

+ unix.ProcessSpec (Folder artifact with process binaries and other files)
  * `configScript` (Script which gets run on deployment per deployed)
