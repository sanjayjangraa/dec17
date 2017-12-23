#!/usr/bin/env groovy
agent {
        docker { image 'ubuntu:latest' }
    }
node {
	sh 'echo "`uptime`  and  `date`"'
	sh 'pwd'
	sh 'ls -l'
}
