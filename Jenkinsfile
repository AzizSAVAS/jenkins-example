pipeline {
    agent any
    stages {
    stage ("verify tooling") {
        steps {
            sh '''
            docker info
            docker info
            docker-compose version
            curl --version
            jq --version
            '''
            }
        }
    }
}