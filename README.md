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
  * `startCommand` (Start command relative to the home directory)
  * `stopCommand` (Stop command relative to the home directory)

+ unix.ProcessSpec (Folder artifact with process binaries and other files)
