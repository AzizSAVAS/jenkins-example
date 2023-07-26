pipleline {
    agent any
    stage {
    stages ("verify tooling") {
        steps {
            sh '''
            docker info
            docker info
            docker compose version
            curl --version
            jq --version
            '''
            }
        }
    }
}