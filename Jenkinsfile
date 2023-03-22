pipeline {
    agent { docker { image 'node:16.17.1-alpine' } }
    triggers {
      githubPush()
    }
    stages {
        stage('build') {
            steps {
                sh 'echo kurt boss'
            }
        }
    }
}
