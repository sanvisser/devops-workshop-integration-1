pipeline {
    agent {
        docker {
            image 'maven:3-alpine'
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
