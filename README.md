# grails-dot-url-problem
Test project to show problems with dots in url in grails applications

To reproduce `StringIndexOutOfBoundsException`"
1. Run application `./grailsw run-app`
2. Access `http://localhost:8080/index/index.`

Expected 404, but you get 500. 