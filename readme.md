A simple demo of testing javascript files and generating code coverage reports using maven + jasmine and saga 
using phatomjs (all of which appear to be no longer supported)

`mvn clean install`

report is in `target/coverage/total-report.html`

http://searls.github.io/jasmine-maven-plugin/code-coverage.html
http://searls.github.io/jasmine-maven-plugin/usage.html
http://timurstrekalov.github.io/saga/
http://htmlunit.sourceforge.net/apidocs/com/gargoylesoftware/htmlunit/BrowserVersion.html

Notes

- if any tests fail, the maven build will fail
- tests are ran twice unfortunately, once for the actual tests and once for code coverage
