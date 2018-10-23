pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
            label 'docker'
            args  '-v /tmp:/tmp'
        }
    }
    stages{
        stage('Build') {
            steps {
                sh "mvn compile"
            }
        }
    }
}
