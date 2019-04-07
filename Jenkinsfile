#!/usr/bin/env groovy

// Configure using microservice-pipelines and using "part2" branch
library identifier: 'shared-library@part3', retriever: modernSCM(
    [$class: 'GitSCMSource',
     remote: 'https://github.com/kcrane3576/microservice-pipelines'])

// Entry point into microservice-pipelines
jenkinsJob.call()

