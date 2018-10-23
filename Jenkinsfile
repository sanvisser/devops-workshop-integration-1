def mvn(String goals){
    sh "mvn -B -s $goals"
}
pipeline {
    stages{
        stage('Compile') {
            mvn compile
        }
    }
}
