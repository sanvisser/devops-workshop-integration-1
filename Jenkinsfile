def mvn(String goals){
    sh "mvn -B -s $goals"
}
pipeline {
    agent any
    stages{
        stage('Build') {
            steps {
                mvn compile
            }
        }
    }
}
