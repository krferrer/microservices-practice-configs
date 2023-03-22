pipeline {
    agent { docker { image 'maven:3.9.0-eclipse-temurin-11' } }
    triggers {
    githubPush()
             }	
	stages {
        stage('build') {
            steps {
                sh 'echo kurt pogi'
            }
        }
    }
}
