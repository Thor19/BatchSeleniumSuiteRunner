# Batch Selenium Suite Runner

The Batch Selenium Suite Runner was created to be able to run multiple selenium test suites without hassle.
Simply configure once the userConfig and run by executing the executable or:

    npm install
    node index.js

The result folder will hold all the reports generated by the selenium standalone server.
This tool will generate a report summary of all the tools and write all output of the execution into a log file.

### Next updates
Because of a broken build of `Selenium Html Runner` this tool was created for `Selenium Standalone Server 2.53.1`
This tool will be updated once the `Selenium Html Runner` is working again

### Run dependecies

- [Firefox v47.0.1](https://ftp.mozilla.org/pub/firefox/releases/47.0.1/)
- [Selenium Standalone Server 2.53.1](http://selenium-release.storage.googleapis.com/index.html?path=2.53/)
- java
- node
- npm

### Build dependencies

  * npm 
  * [nexe dependencies](https://github.com/nexe/nexe#building-requirements)
      * npm install -g windows-build-tools
      * python 2.7


### How to Build
    clone git@github.com:Sigurthorb/BatchSeleniumSuiteRunner.git
    npm install
    npm run build

#### Frequent issues
- If firefox browser does not close after execution of a test suite the browser needs to be configured to not ask if you want to close multiple tabs. [FIX](https://support.mozilla.org/t5/Manage-preferences-and-add-ons/Tab-preferences-and-settings/ta-p/3683)
